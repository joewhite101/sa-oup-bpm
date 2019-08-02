       	
       	JBOSS SYSTEM PROPERTIES
       	
       	
       	<!--          sa oup bpm : RestErrorHandling parameters         -->

        <property name="exceptionHandler" value="it.poste.o2c.saoupbpm.RestErrorHandlerProcess"/>
        <property name="MaxAttemptNum" value="5"/>
        <property name="TimeUnit" value="60"/>
        
        <!--          Service Activator Integration sa-oup-attivazione          -->

        <property name="posteGateway_attivazione" value="http://localhost:8976/service-activator/posteit/gateway"/>
        <property name="nbepGateway_attivazione" value="http://localhost:8666/integration-layer/nbep/gateway"/>
         <property name="sfaGateway_attivazione" value="http://localhost:28960/service-activator/sfa/gateway"/>
         <property name="portaleOffertaUnicaGateway_attivazione" value="http://localhost:8777/service-activator/poup/gateway"/>

       <!--          Service Activator Integration  sa-oup-disattivazione          -->
        
        <property name="posteGateway_disattivazione" value="http://sa-service:8888/service-activator/poste-notifica-disattivazione"/>
        <property name="nbepGateway_disattivazione" value="http://sa-service:8888/service-activator/nbep-notifica-disattivazione"/>
        <property name="sfaGateway_disattivazione" value="http://sa-service:8888/service-activator/sfa-notifica-disattivazione"/>
        <property name="portaleOffertaUnicaGateway_disattivazione" value="http://sa-service:8888/service-activator/pou-notifica-disattivazione"/>

		<!--          Service Activator Integration sa-oup-sospensione          -->

        <property name="nbepGateway_sospensione" value="http://sa-service:8888/service-activator/nbep-notifica-disattivazione"/>
        <property name="sfaGateway_sospensione" value="http://sa-service:8888/service-activator/sfa-notifica-disattivazione"/>


        <property name="it.poste.o2c.sa.integration.utility.process-callback.url" value="http://localhost:8888/service-activator/utility"/>



        <!-- Signal Names (to dismiss) -->

        <property name="oupdisattivazione_okposte_0" value="ok_poste_0"/>
        <property name="oupdisattivazione_oknbep_0" value="ok_nbep_0"/>
        <property name="oupdisattivazione_okpou_0" value="ok_pou_0"/>
        <property name="oupattivazione_okposte_0" value="ok_poste_0"/>
        <property name="oupattivazione_oknbep_0" value="ok_nbep_0"/>
        <property name="oupattivazione_okpou_0" value="ok_pou_0"/>
        <property name="oupsospensione_oknbep_0" value="ok_nbep_0"/>