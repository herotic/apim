# gateway 9.4
<pre>
/opt
└── SecureSpan
    ├── Controller
    │   ├── bin
    │   │   ├── patch.sh
    │   │   ├── pc.sh
    │   │   └── processcontroller.sh
    │   ├── Controller.jar
    │   ├── etc
    │   │   └── conf
    │   │       └── omp.dat
    │   ├── lib
    │   │   ├── annotations-java8-2016.2.5.jar
    │   │   ├── aopalliance-1.0.jar
    │   │   ├── apacheds-i18n-2.0.0-M21.jar
    │   │   ├── apacheds-kerberos-codec-2.0.0-M21.jar
    │   │   ├── apache-harmony-asn1-0.1.jar
    │   │   ├── api-asn1-api-1.0.0-M33.jar
    │   │   ├── api-asn1-ber-1.0.0-M33.jar
    │   │   ├── api-i18n-1.0.0-M33.jar
    │   │   ├── api-ldap-model-1.0.0-M33.jar
    │   │   ├── api-util-1.0.0-M33.jar
    │   │   ├── asm-3.3.1.jar
    │   │   ├── bcpkix-jdk15on-1.60.jar
    │   │   ├── bcprov-jdk15on-1.60.jar
    │   │   ├── commons-codec-1.6.jar
    │   │   ├── commons-collections-3.2.2.jar
    │   │   ├── commons-configuration-1.8.jar
    │   │   ├── commons-lang-2.6.jar
    │   │   ├── commons-lang3-3.2.1.jar
    │   │   ├── commons-pool-1.6.jar
    │   │   ├── concurrent-1.3.4.jar
    │   │   ├── cryptocomply-2.2.1.jar
    │   │   ├── cxf-api-2.5.11.jar
    │   │   ├── cxf-common-utilities-2.5.11.jar
    │   │   ├── cxf-rt-bindings-soap-2.5.11.jar
    │   │   ├── cxf-rt-bindings-xml-2.5.11.jar
    │   │   ├── cxf-rt-core-2.5.11.jar
    │   │   ├── cxf-rt-databinding-jaxb-2.5.11.jar
    │   │   ├── cxf-rt-frontend-jaxws-2.5.11.jar
    │   │   ├── cxf-rt-frontend-simple-2.5.11.jar
    │   │   ├── cxf-rt-transports-common-2.5.11.jar
    │   │   ├── cxf-rt-transports-http-2.5.11.jar
    │   │   ├── cxf-rt-transports-http-jetty-2.5.11.jar
    │   │   ├── cxf-rt-ws-addr-2.5.11.jar
    │   │   ├── cxf-tools-common-2.5.11.jar
    │   │   ├── dom4j-1.6.1.jar
    │   │   ├── ehcache-2.10.3.jar
    │   │   ├── HMacSP800DRBGResync-2.2.1.jar
    │   │   ├── httpclient-4.2.5.jar
    │   │   ├── httpcore-4.2.4.jar
    │   │   ├── httpmime-4.2.5.jar
    │   │   ├── jaaslounge-decoding-2.0-l7p3-SNAPSHOT.jar
    │   │   ├── jackson-annotations-2.8.6.jar
    │   │   ├── jackson-core-2.8.6.jar
    │   │   ├── jackson-core-asl-1.9.7.jar
    │   │   ├── jackson-databind-2.8.6.jar
    │   │   ├── jackson-mapper-asl-1.9.7.jar
    │   │   ├── javax.inject-1.jar
    │   │   ├── javax.servlet-api-3.0.1.jar
    │   │   ├── jaxb-api-2.1.jar
    │   │   ├── jaxb-impl-2.1.13.jar
    │   │   ├── jaxen-1.1.4.jar
    │   │   ├── jaxws-api-2.1.jar
    │   │   ├── jaxws-rt-2.1.7.jar
    │   │   ├── jbosscache-core-3.2.5.GA.jar
    │   │   ├── jboss-common-core-2.2.14.GA.jar
    │   │   ├── jboss-j2ee-4.0.5.GA.jar
    │   │   ├── jboss-logging-spi-2.0.5.GA.jar
    │   │   ├── jcifs-1.3.17.jar
    │   │   ├── jcip-annotations-1.0.jar
    │   │   ├── jcl-over-slf4j-1.6.6.jar
    │   │   ├── jdom-1.1.3.jar
    │   │   ├── jetty-6.1.26-l7p.jar
    │   │   ├── jetty-util-6.1.26-l7p.jar
    │   │   ├── jgroups-2.6.15.GA.jar
    │   │   ├── json-schema-validator-0.0.1-SNAPSHOT.jar
    │   │   ├── json-schema-validator-0.1.6.l7p1.jar
    │   │   ├── kerb-client-1.0.0-RC2.jar
    │   │   ├── kerb-client-api-all-1.0.0-RC2.jar
    │   │   ├── kerb-common-1.0.0-RC2.jar
    │   │   ├── kerb-core-1.0.0-RC2.jar
    │   │   ├── kerb-crypto-1.0.0-RC2.jar
    │   │   ├── kerb-util-1.0.0-RC2.jar
    │   │   ├── kerby-asn1-1.0.0-RC2.jar
    │   │   ├── kerby-config-1.0.0-RC2.jar
    │   │   ├── kerby-pkix-1.0.0-RC2.jar
    │   │   ├── kerby-util-1.0.0-RC2.jar
    │   │   ├── layer7-common-9.4.00.jar
    │   │   ├── layer7-config-9.4.00.jar
    │   │   ├── layer7-gateway-api-1.2.jar
    │   │   ├── layer7-gateway-common-9.4.00.jar
    │   │   ├── layer7-gateway-config-9.4.00.jar
    │   │   ├── layer7-gateway-management-9.4.00.jar
    │   │   ├── layer7-gateway-server-9.4.00.jar
    │   │   ├── layer7-identity-9.4.00.jar
    │   │   ├── layer7-json-9.4.00.jar
    │   │   ├── layer7-kerberos-9.4.00.jar
    │   │   ├── layer7-ntlm-9.4.00.jar
    │   │   ├── layer7-policy-9.4.00.jar
    │   │   ├── layer7-uddi-9.4.00.jar
    │   │   ├── layer7-uddi-lib-1.1.0.jar
    │   │   ├── layer7-utility-9.4.00.jar
    │   │   ├── layer7-wsdl-9.4.00.jar
    │   │   ├── liquibase-3.2.2.jar
    │   │   ├── log4j-over-slf4j-1.6.6.jar
    │   │   ├── mail-1.6.1.jar
    │   │   ├── mina-core-2.0.7.jar
    │   │   ├── mockwebserver-20130505.jar
    │   │   ├── mysql-connector-java-5.1.46.jar
    │   │   ├── neethi-3.0.2.jar
    │   │   ├── nekohtml-1.9.15.jar
    │   │   ├── ntlmv2-lib-1.0.4.jar
    │   │   ├── persistence-api-2.0.0.jar
    │   │   ├── policy-1.0.jar
    │   │   ├── saxon9ee-9.4.0.9.jar
    │   │   ├── servlet-api-2.5.jar
    │   │   ├── servlet-api-resources-2.5.jar
    │   │   ├── sftp-8.8.1.jar
    │   │   ├── slf4j-api-1.6.6.jar
    │   │   ├── slf4j-ext-1.6.5.jar
    │   │   ├── slf4j-jdk14-1.6.6.jar
    │   │   ├── snmp4j-1.11.3.jar
    │   │   ├── spring-aop-3.0.7.RELEASE.jar
    │   │   ├── spring-asm-3.0.7.RELEASE.jar
    │   │   ├── spring-beans-3.0.7.RELEASE.jar
    │   │   ├── spring-context-3.0.7.RELEASE.jar
    │   │   ├── spring-context-support-3.0.7.RELEASE.jar
    │   │   ├── spring-core-3.0.7.RELEASE.jar
    │   │   ├── spring-expression-3.0.7.RELEASE.jar
    │   │   ├── spring-jdbc-3.0.7.RELEASE.jar
    │   │   ├── spring-orm-3.0.7.RELEASE.jar
    │   │   ├── spring-tx-3.0.7.RELEASE.jar
    │   │   ├── spring-web-3.0.7.RELEASE.jar
    │   │   ├── stax2-api-3.1.1.jar
    │   │   ├── stax-api-1.0-2.jar
    │   │   ├── stax-ex-1.2.jar
    │   │   ├── streambuffer-0.8.jar
    │   │   ├── validation-api-1.0.0.GA.jar
    │   │   ├── whirlycache-1.0.1-l7p1.jar
    │   │   ├── woodstox-core-asl-4.2.0.jar
    │   │   ├── wsdl4j-1.6.2-l7p3.jar
    │   │   ├── xalan-2.7.2-l7p1.jar
    │   │   ├── xalan-serializer-2.7.2.jar
    │   │   ├── xbean-saml-1.1-1.0.jar
    │   │   ├── xbean-saml-2.0-1.0.jar
    │   │   ├── xbean-xenc-xmldsig-1.0.jar
    │   │   ├── xercesImpl-2.11.0-l7p1.jar
    │   │   ├── xml-apis-1.4.01.jar
    │   │   ├── xmlbeans-2.5.0.jar
    │   │   ├── xml-resolver-1.2.jar
    │   │   ├── xmlschema-core-2.0.3.jar
    │   │   ├── xmlsec-1.5.7.jar
    │   │   ├── xom-1.2.8.jar
    │   │   ├── xss4j.00.patch-1.1.jar
    │   │   └── xss4j-1.0.jar
    │   └── var
    │       ├── logs
    │       ├── patches
    │       └── run
    └── Gateway
        ├── config
        │   ├── backup
        │   │   ├── backupgatewaylogging.properties
        │   │   ├── backuputilitylogging.properties
        │   │   ├── cfg
        │   │   │   ├── backup_tables_audit
        │   │   │   ├── exclude_files
        │   │   │   └── exclude_tables
        │   │   ├── images
        │   │   ├── logs
        │   │   ├── restore_logging.properties
        │   │   ├── ssgbackup.sh
        │   │   ├── SSGBackupUtility.jar
        │   │   ├── ssgmigrate.sh
        │   │   └── ssgrestore.sh
        │   ├── bin
        │   │   └── ssgconfig-headless
        │   ├── ConfigClusterAddress.jar
        │   ├── ConfigClusterPassphrase.jar
        │   ├── ConfigHeadless.jar
        │   ├── ConfigKeystoreFileProperty.jar
        │   ├── configlogging.properties
        │   ├── ConfigMasterPassphrase.jar
        │   ├── ConfigProcessController.jar
        │   ├── ConfigWizard.jar
        │   ├── DatabaseUpgrader.jar
        │   ├── etc
        │   │   ├── db
        │   │   │   ├── ssg-8.2.00.xml
        │   │   │   ├── ssg-base.xml
        │   │   │   ├── ssg-data-roles.xml
        │   │   │   ├── ssg-data.xml
        │   │   │   ├── ssg-upgrade.xml
        │   │   │   ├── ssg.xml
        │   │   │   ├── upgrade_8.3.00.xml
        │   │   │   ├── upgrade_8.4.00.xml
        │   │   │   ├── upgrade_9.0.00.xml
        │   │   │   ├── upgrade_9.1.00.xml
        │   │   │   ├── upgrade_9.2.00.xml
        │   │   │   ├── upgrade_9.3.00.xml
        │   │   │   └── upgrade_9.4.00.xml
        │   │   └── sql
        │   │       ├── externalAudits_db2.sql
        │   │       ├── externalAudits_mysql.sql
        │   │       ├── externalAudits_oracle.sql
        │   │       ├── externalAudits_sqlserver.sql
        │   │       ├── upgrade_7.0.0-7.0.2_success.sql
        │   │       ├── upgrade_7.0.0-7.0.2_try.sql
        │   │       ├── upgrade_7.0.2-7.1.0.sql
        │   │       ├── upgrade_7.1.0-7.1.1_success.sql
        │   │       ├── upgrade_7.1.0-7.1.1_try.sql
        │   │       ├── upgrade_7.1.1-8.0.0.sql
        │   │       ├── upgrade_8.0.0-8.1.0.sql
        │   │       ├── upgrade_8.1.02-8.2.00.sql
        │   │       ├── upgrade_8.1.0-8.1.1.sql
        │   │       ├── upgrade_8.1.1-8.1.02.sql
        │   │       ├── upgrade_8.2.00-8.2.01.sql
        │   │       └── upgrade_8.2.01-8.3.pre.sql
        │   ├── logs
        │   ├── PasswordReset.jar
        │   └── ssgconfig.sh
        ├── node
        │   └── default
        │       ├── etc
        │       │   └── conf
        │       │       ├── omp.dat
        │       │       ├── ssglog.properties
        │       │       ├── system.properties
        │       │       └── trusted_signers
        │       └── var
        │           ├── attachments
        │           ├── logs
        │           ├── messagecache
        │           └── modstaging
        └── runtime
            ├── bin
            │   ├── dbtool.sh
            │   ├── gateway.sh
            │   ├── samples
            │   │   └── fix_banner.sh
            │   ├── setup.sh
            │   └── upgrade.sh
            ├── etc
            │   ├── profile
            │   ├── profile.d
            │   │   ├── siteminder-env.sh
            │   │   ├── ssgnodedefs.sh
            │   │   ├── ssgruntimedefs.sh
            │   │   ├── ssg-utilities.sh
            │   │   └── xlocaldefs.sh
            │   └── ssg.policy
            ├── Gateway.jar
            ├── lib
            │   ├── alt
            │   ├── annotations-api-6.0.53.jar
            │   ├── annotations-java8-2016.2.5.jar
            │   ├── antlr-2.7.7-l7p1.jar
            │   ├── aopalliance-1.0.jar
            │   ├── apacheds-i18n-2.0.0-M21.jar
            │   ├── apacheds-kerberos-codec-2.0.0-M21.jar
            │   ├── apache-harmony-asn1-0.1.jar
            │   ├── api-asn1-api-1.0.0-M33.jar
            │   ├── api-asn1-ber-1.0.0-M33.jar
            │   ├── api-i18n-1.0.0-M33.jar
            │   ├── api-ldap-model-1.0.0-M33.jar
            │   ├── api-util-1.0.0-M33.jar
            │   ├── asm-3.3.1.jar
            │   ├── aspectjweaver-1.6.12.jar
            │   ├── bcpkix-jdk15on-1.60.jar
            │   ├── bcprov-jdk15on-1.60.jar
            │   ├── c3p0-0.9.1.2.jar
            │   ├── cassandra-driver-core-3.1.0.jar
            │   ├── catalina-6.0.53-l7p1.jar
            │   ├── cglib-nodep-2.2.2.jar
            │   ├── commons-beanutils-1.9.0.jar
            │   ├── commons-codec-1.6.jar
            │   ├── commons-collections-3.2.2.jar
            │   ├── commons-compress-1.10.jar
            │   ├── commons-configuration-1.8.jar
            │   ├── commons-digester-2.1.jar
            │   ├── commons-io-2.3.jar
            │   ├── commons-lang-2.6.jar
            │   ├── commons-lang3-3.2.1.jar
            │   ├── commons-pool-1.6.jar
            │   ├── concurrent-1.3.4.jar
            │   ├── coyote-6.0.53-l7p2.jar
            │   ├── cryptocomply-2.2.1.hmac
            │   ├── cryptocomply-2.2.1.jar
            │   ├── cxf-api-2.5.11.jar
            │   ├── cxf-common-utilities-2.5.11.jar
            │   ├── cxf-rt-bindings-soap-2.5.11.jar
            │   ├── cxf-rt-bindings-xml-2.5.11.jar
            │   ├── cxf-rt-core-2.5.11.jar
            │   ├── cxf-rt-databinding-jaxb-2.5.11.jar
            │   ├── cxf-rt-frontend-jaxws-2.5.11.jar
            │   ├── cxf-rt-frontend-simple-2.5.11.jar
            │   ├── cxf-rt-transports-common-2.5.11.jar
            │   ├── cxf-rt-transports-http-2.5.11.jar
            │   ├── cxf-rt-transports-http-jetty-2.5.11.jar
            │   ├── cxf-rt-ws-addr-2.5.11.jar
            │   ├── cxf-tools-common-2.5.11.jar
            │   ├── derby-10.7.1.1.jar
            │   ├── dom4j-1.6.1.jar
            │   ├── ecj-4.3.1.jar
            │   ├── ehcache-2.10.3.jar
            │   ├── ext
            │   │   └── jms-1.1.jar
            │   ├── extension-api-9.4.00.jar
            │   ├── ftplet-api-1.0.6.jar
            │   ├── ftpserver-core-1.0.6.jar
            │   ├── guava-16.0.1.jar
            │   ├── hibernate-commons-annotations-3.2.0.Final.jar
            │   ├── hibernate-core-3.6.9.Final.jar
            │   ├── hibernate-ehcache-3.6.9.jar
            │   ├── hibernate-validator-4.1.0.Final.jar
            │   ├── hk2-api-2.2.0.21.jar
            │   ├── hk2-locator-2.2.0.21.jar
            │   ├── hk2-utils-2.2.0.21.jar
            │   ├── HMacSP800DRBGResync-2.2.1.jar
            │   ├── httpclient-4.2.5.jar
            │   ├── httpcore-4.2.4.jar
            │   ├── httpmime-4.2.5.jar
            │   ├── iText-2.1.7.js2-2.1.7.jar
            │   ├── jaaslounge-decoding-2.0-l7p3-SNAPSHOT.jar
            │   ├── jackson-annotations-2.8.6.jar
            │   ├── jackson-core-2.8.6.jar
            │   ├── jackson-core-asl-1.9.7.jar
            │   ├── jackson-databind-2.8.6.jar
            │   ├── jackson-mapper-asl-1.9.7.jar
            │   ├── jasperreports-6.1.0-p1.jar
            │   ├── javassist-3.19.0-GA.jar
            │   ├── javax.annotation-api-1.2.jar
            │   ├── javax.inject-1.jar
            │   ├── javax.servlet-api-3.0.1.jar
            │   ├── javax.ws.rs-api-2.0.jar
            │   ├── jaxb-api-2.1.jar
            │   ├── jaxb-impl-2.1.13.jar
            │   ├── jaxen-1.1.4.jar
            │   ├── jaxws-api-2.1.jar
            │   ├── jaxws-rt-2.1.7.jar
            │   ├── jbosscache-core-3.2.5.GA.jar
            │   ├── jboss-common-core-2.2.14.GA.jar
            │   ├── jboss-j2ee-4.0.5.GA.jar
            │   ├── jboss-logging-spi-2.0.5.GA.jar
            │   ├── jcifs-1.3.17.jar
            │   ├── jcip-annotations-1.0.jar
            │   ├── jcl-over-slf4j-1.6.6.jar
            │   ├── jcommon-1.0.17.jar
            │   ├── jdom-1.1.3.jar
            │   ├── jersey-client-2.5.1.jar
            │   ├── jersey-common-2.5.1.jar
            │   ├── jersey-media-multipart-2.5.1.jar
            │   ├── jersey-server-2.5.1.jar
            │   ├── jfreechart-1.0.14.jar
            │   ├── jgroups-2.6.15.GA.jar
            │   ├── jnlp-servlet-1.0.jar
            │   ├── jsch-0.1.49.jar
            │   ├── json-schema-validator-0.0.1-SNAPSHOT.jar
            │   ├── json-schema-validator-0.1.6.l7p1.jar
            │   ├── jta-1.1.jar
            │   ├── juli-6.0.53.jar
            │   ├── kerb-client-1.0.0-RC2.jar
            │   ├── kerb-client-api-all-1.0.0-RC2.jar
            │   ├── kerb-common-1.0.0-RC2.jar
            │   ├── kerb-core-1.0.0-RC2.jar
            │   ├── kerb-crypto-1.0.0-RC2.jar
            │   ├── kerb-util-1.0.0-RC2.jar
            │   ├── kerby-asn1-1.0.0-RC2.jar
            │   ├── kerby-config-1.0.0-RC2.jar
            │   ├── kerby-pkix-1.0.0-RC2.jar
            │   ├── kerby-util-1.0.0-RC2.jar
            │   ├── L7db2-5.1.4.patch.jar
            │   ├── L7mysql-5.1.4.patch.jar
            │   ├── L7oracle-5.1.4.patch.jar
            │   ├── L7sqlserver-5.1.4.patch.jar
            │   ├── layer7-cassandra-9.4.00.jar
            │   ├── layer7-common-9.4.00.jar
            │   ├── layer7-config-9.4.00.jar
            │   ├── layer7-gateway-api-1.2.jar
            │   ├── layer7-gateway-common-9.4.00.jar
            │   ├── layer7-gateway-config-9.4.00.jar
            │   ├── layer7-gateway-management-9.4.00.jar
            │   ├── layer7-gateway-reporting-9.4.00.jar
            │   ├── layer7-gateway-rest-toolkit-9.4.00.jar
            │   ├── layer7-gateway-sca-common-9.4.00.jar
            │   ├── layer7-identity-9.4.00.jar
            │   ├── layer7-json-9.4.00.jar
            │   ├── layer7-kerberos-9.4.00.jar
            │   ├── layer7-ntlm-9.4.00.jar
            │   ├── layer7-policy-9.4.00.jar
            │   ├── layer7-policy-exporter-9.4.00.jar
            │   ├── layer7-siteminder-9.4.00.jar
            │   ├── layer7-sun-jaxws-1.0.jar
            │   ├── layer7-uddi-9.4.00.jar
            │   ├── layer7-uddi-lib-1.1.0.jar
            │   ├── layer7-utility-9.4.00.jar
            │   ├── layer7-wsdl-9.4.00.jar
            │   ├── liquibase-3.2.2.jar
            │   ├── log4j-over-slf4j-1.6.6.jar
            │   ├── lz4-1.3-nodynamiclib.jar
            │   ├── mail-1.6.1.jar
            │   ├── metrics-core-3.0.2.jar
            │   ├── mimepull-1.9.2.jar
            │   ├── mina-core-2.0.7.jar
            │   ├── mockwebserver-20130505.jar
            │   ├── mysql-connector-java-5.1.46.jar
            │   ├── neethi-3.0.2.jar
            │   ├── nekohtml-1.9.15.jar
            │   ├── netty-all-4.1.1.Final.jar
            │   ├── ntlmv2-lib-1.0.4.jar
            │   ├── persistence-api-2.0.0.jar
            │   ├── policy-1.0.jar
            │   ├── quartz-2.2.1.jar
            │   ├── saxon9ee-9.4.0.9.jar
            │   ├── servlet-api-resources-2.5.jar
            │   ├── sftp-8.8.1.jar
            │   ├── slf4j-api-1.6.6.jar
            │   ├── slf4j-ext-1.6.5.jar
            │   ├── slf4j-jdk14-1.6.6.jar
            │   ├── smjavaagentapi-12.52.jar
            │   ├── SmJavaApi-12.52.jar
            │   ├── smjavasdk2-12.52.jar
            │   ├── spring-aop-3.0.7.RELEASE.jar
            │   ├── spring-asm-3.0.7.RELEASE.jar
            │   ├── spring-beans-3.0.7.RELEASE.jar
            │   ├── spring-context-3.0.7.RELEASE.jar
            │   ├── spring-context-support-3.0.7.RELEASE.jar
            │   ├── spring-core-3.0.7.RELEASE.jar
            │   ├── spring-expression-3.0.7.RELEASE.jar
            │   ├── spring-jdbc-3.0.7.RELEASE.jar
            │   ├── spring-orm-3.0.7.RELEASE.jar
            │   ├── spring-tx-3.0.7.RELEASE.jar
            │   ├── spring-web-3.0.7.RELEASE.jar
            │   ├── spring-web-servlet-3.0.7.RELEASE.jar
            │   ├── stax2-api-3.1.1.jar
            │   ├── stax-api-1.0-2.jar
            │   ├── stax-ex-1.2.jar
            │   ├── streambuffer-0.8.jar
            │   ├── validation-api-1.0.0.GA.jar
            │   ├── whirlycache-1.0.1-l7p1.jar
            │   ├── wiseman-1.0.jar
            │   ├── woodstox-core-asl-4.2.0.jar
            │   ├── wsdl4j-1.6.2-l7p3.jar
            │   ├── xalan-2.7.2-l7p1.jar
            │   ├── xalan-serializer-2.7.2.jar
            │   ├── xbean-saml-1.1-1.0.jar
            │   ├── xbean-saml-2.0-1.0.jar
            │   ├── xbean-xenc-xmldsig-1.0.jar
            │   ├── xercesImpl-2.11.0-l7p1.jar
            │   ├── xml-apis-1.4.01.jar
            │   ├── xmlbeans-2.5.0.jar
            │   ├── xml-resolver-1.2.jar
            │   ├── xmlschema-core-2.0.3.jar
            │   ├── xmlsec-1.5.7.jar
            │   ├── xom-1.2.8.jar
            │   ├── xss4j.00.patch-1.1.jar
            │   └── xss4j-1.0.jar
            ├── modules
            │   ├── assertions
            │   │   ├── AdaptiveLoadBalancingAssertion-9.4.00.aar
            │   │   ├── BufferDataAssertion-9.4.00.aar
            │   │   ├── BulkJdbcInsertAssertion-9.4.00.aar
            │   │   ├── CacheAssertion-9.4.00.aar
            │   │   ├── CassandraAssertion-9.4.00.aar
            │   │   ├── CertificateAttributesAssertion-9.4.00.aar
            │   │   ├── CircuitBreakerAssertion-9.4.00.aar
            │   │   ├── ComparisonAssertion-9.4.00.aar
            │   │   ├── ConcurrentAllAssertion-9.4.00.aar
            │   │   ├── CORSAssertion-9.4.00.aar
            │   │   ├── CsrfProtectionAssertion-9.4.00.aar
            │   │   ├── CsrSignerAssertion-9.4.00.aar
            │   │   ├── EchoRoutingAssertion-1.0.00.aar
            │   │   ├── EmailAssertion-9.4.00.aar
            │   │   ├── EmbeddedHazelcastSharedStateProviderAssertion-1.0.00.aar
            │   │   ├── EncodeDecodeAssertion-9.4.00.aar
            │   │   ├── EsmAssertion-9.4.00.aar
            │   │   ├── EvaluateJsonPathExpressionAssertion-9.4.00.aar
            │   │   ├── EvaluateJsonPathExpressionV2Assertion-9.4.00.aar
            │   │   ├── ExternalHazelcastSharedStateProviderAssertion-1.0.00.aar
            │   │   ├── FtpCredentialAssertion-9.4.00.aar
            │   │   ├── FtpRoutingAssertion-9.4.00.aar
            │   │   ├── GatewayManagementAssertion-9.4.00.aar
            │   │   ├── GenerateOAuthSignatureBaseStringAssertion-9.4.00.aar
            │   │   ├── GenerateSecurityHashAssertion-9.4.00.aar
            │   │   ├── GenericIdentityManagementServiceAssertion-9.4.00.aar
            │   │   ├── IcapAntivirusScannerAssertion-9.4.00.aar
            │   │   ├── IdentityAttributesAssertion-9.4.00.aar
            │   │   ├── JavaScriptAssertion-1.0.00.aar
            │   │   ├── JdbcQueryAssertion-9.4.00.aar
            │   │   ├── JsonDocumentStructureAssertion-9.4.00.aar
            │   │   ├── JSONSchemaAssertion-9.4.00.aar
            │   │   ├── JsonTransformationAssertion-9.4.00.aar
            │   │   ├── JsonWebTokenAssertion-9.4.00.aar
            │   │   ├── JwtAssertion-9.4.00.aar
            │   │   ├── KerberosAuthenticationAssertion-9.4.00.aar
            │   │   ├── LDAPQueryAssertion-9.4.00.aar
            │   │   ├── LdapWriteAssertion-9.4.00.aar
            │   │   ├── LookupDynamicContextVariablesAssertion-9.4.00.aar
            │   │   ├── ManageCookieAssertion-9.4.00.aar
            │   │   ├── ManipulateMultiValuedVariableAssertion-9.4.00.aar
            │   │   ├── MessageContextAssertion-9.4.00.aar
            │   │   ├── MqNativeAssertion-9.4.00.aar
            │   │   ├── MTOMAssertion-9.4.00.aar
            │   │   ├── MysqlClusterInfoAssertion-9.4.00.aar
            │   │   ├── MysqlCounterAssertion-9.4.00.aar
            │   │   ├── NcesDecoratorAssertion-9.4.00.aar
            │   │   ├── NcesValidatorAssertion-9.4.00.aar
            │   │   ├── NtlmAuthenticationAssertion-9.4.00.aar
            │   │   ├── OdataValidationAssertion-9.4.00.aar
            │   │   ├── PolicyBackedServiceMetricsEventListener-1.0.00.aar
            │   │   ├── PolicyBundleInstallerAssertion-9.4.00.aar
            │   │   ├── PortalBootstrapAssertion-9.4.00.aar
            │   │   ├── RadiusAssertion-9.4.00.aar
            │   │   ├── RateLimitAssertion-9.4.00.aar
            │   │   ├── ReplaceTagContentAssertion-9.4.00.aar
            │   │   ├── RetrieveServiceWsdlAssertion-9.4.00.aar
            │   │   ├── SamlIssuerAssertion-9.4.00.aar
            │   │   ├── SamlpAssertion-9.4.00.aar
            │   │   ├── SimpleRawTransportAssertion-9.4.00.aar
            │   │   ├── SiteMinderAssertion-9.4.00.aar
            │   │   ├── SnmpTrapAssertion-9.4.00.aar
            │   │   ├── SplitJoinAssertion-9.4.00.aar
            │   │   ├── SshAssertion-9.4.00.aar
            │   │   ├── SwaggerAssertion-9.4.00.aar
            │   │   ├── ThroughputQuotaAssertion-9.4.00.aar
            │   │   ├── UDDINotificationAssertion-9.4.00.aar
            │   │   ├── UUIDGeneratorAssertion-9.4.00.aar
            │   │   ├── ValidateCertificateAssertion-9.4.00.aar
            │   │   ├── ValidateNonSoapSamlAssertion-9.4.00.aar
            │   │   ├── WebSocketAssertion-9.4.00.aar
            │   │   ├── WsAddressingAssertion-9.4.00.aar
            │   │   ├── XacmlPdpAssertion-9.4.00.aar
            │   │   ├── XmlSecurityAssertion-9.4.00.aar
            │   │   └── XMPPAssertion-9.4.00.aar
            │   ├── conf
            │   └── lib
            │       └── OpenIDConnectAssertion-b753.jar
            └── web
                └── ssg
                    ├── README.md
                    ├── webadmin
                    │   └── applet
                    │       ├── layer7-gateway-console-applet.jar
                    │       ├── layer7-gateway-console-applet.jar.pack.gz
                    │       └── lib
                    │           ├── annotations-java8-2016.2.5.jar
                    │           ├── annotations-java8-2016.2.5.jar.pack.gz
                    │           ├── antlr-2.7.7-l7p1.jar
                    │           ├── antlr-2.7.7-l7p1.jar.pack.gz
                    │           ├── aopalliance-1.0.jar
                    │           ├── aopalliance-1.0.jar.pack.gz
                    │           ├── apacheds-i18n-2.0.0-M21.jar
                    │           ├── apacheds-kerberos-codec-2.0.0-M21.jar
                    │           ├── apache-harmony-asn1-0.1.jar
                    │           ├── apache-harmony-asn1-0.1.jar.pack.gz
                    │           ├── api-asn1-api-1.0.0-M33.jar
                    │           ├── api-asn1-ber-1.0.0-M33.jar
                    │           ├── api-i18n-1.0.0-M33.jar
                    │           ├── api-ldap-model-1.0.0-M33.jar
                    │           ├── api-util-1.0.0-M33.jar
                    │           ├── bcpkix-jdk15on-1.60.jar
                    │           ├── bcprov-unsigned-jdk15on-1.60.jar
                    │           ├── bcprov-unsigned-jdk15on-1.60.jar.pack.gz
                    │           ├── browser-launcher-1.0rc4.jar
                    │           ├── browser-launcher-1.0rc4.jar.pack.gz
                    │           ├── commons-codec-1.6.jar
                    │           ├── commons-codec-1.6.jar.pack.gz
                    │           ├── commons-collections-3.2.2.jar
                    │           ├── commons-collections-3.2.2.jar.pack.gz
                    │           ├── commons-compress-1.10.jar
                    │           ├── commons-lang-2.6.jar
                    │           ├── commons-lang-2.6.jar.pack.gz
                    │           ├── commons-lang3-3.2.1.jar
                    │           ├── commons-pool-1.6.jar
                    │           ├── concurrent-1.3.4.jar
                    │           ├── concurrent-1.3.4.jar.pack.gz
                    │           ├── cryptocomply-2.2.1.jar
                    │           ├── dom4j-1.6.1.jar
                    │           ├── dom4j-1.6.1.jar.pack.gz
                    │           ├── ehcache-2.10.3.jar
                    │           ├── forms_rt-2016.2.5.jar
                    │           ├── forms_rt-2016.2.5.jar.pack.gz
                    │           ├── hibernate-core-3.6.9.Final.jar
                    │           ├── hibernate-core-3.6.9.Final.jar.pack.gz
                    │           ├── HMacSP800DRBGResync-2.2.1.jar
                    │           ├── httpclient-4.2.5.jar
                    │           ├── httpclient-4.2.5.jar.pack.gz
                    │           ├── httpcore-4.2.4.jar
                    │           ├── httpcore-4.2.4.jar.pack.gz
                    │           ├── httpmime-4.2.5.jar
                    │           ├── httpmime-4.2.5.jar.pack.gz
                    │           ├── jaaslounge-decoding-2.0-l7p3-SNAPSHOT.jar
                    │           ├── jackson-annotations-2.8.6.jar
                    │           ├── jackson-core-2.8.6.jar
                    │           ├── jackson-core-asl-1.9.7.jar
                    │           ├── jackson-core-asl-1.9.7.jar.pack.gz
                    │           ├── jackson-databind-2.8.6.jar
                    │           ├── jackson-mapper-asl-1.9.7.jar
                    │           ├── jackson-mapper-asl-1.9.7.jar.pack.gz
                    │           ├── javax.servlet-api-3.0.1.jar
                    │           ├── javax.servlet-api-3.0.1.jar.pack.gz
                    │           ├── jaxb-api-2.1.jar
                    │           ├── jaxb-api-2.1.jar.pack.gz
                    │           ├── jaxb-impl-2.1.13.jar
                    │           ├── jaxb-impl-2.1.13.jar.pack.gz
                    │           ├── jaxen-1.1.4.jar
                    │           ├── jaxen-1.1.4.jar.pack.gz
                    │           ├── jaxws-api-2.1.jar
                    │           ├── jaxws-api-2.1.jar.pack.gz
                    │           ├── jaxws-rt-2.1.7.jar
                    │           ├── jaxws-rt-2.1.7.jar.pack.gz
                    │           ├── jbosscache-core-3.2.5.GA.jar
                    │           ├── jboss-common-core-2.2.14.GA.jar
                    │           ├── jboss-j2ee-4.0.5.GA.jar
                    │           ├── jboss-logging-spi-2.0.5.GA.jar
                    │           ├── jcalendar-1.4.jar
                    │           ├── jcalendar-1.4.jar.pack.gz
                    │           ├── jcifs-1.3.17.jar
                    │           ├── jcip-annotations-1.0.jar
                    │           ├── jcl-over-slf4j-1.6.6.jar
                    │           ├── jcl-over-slf4j-1.6.6.jar.pack.gz
                    │           ├── jcommon-1.0.17.jar
                    │           ├── jcommon-1.0.17.jar.pack.gz
                    │           ├── jdom-1.1.3.jar
                    │           ├── jdom-1.1.3.jar.pack.gz
                    │           ├── jfreechart-1.0.14.jar
                    │           ├── jfreechart-1.0.14.jar.pack.gz
                    │           ├── jgroups-2.6.15.GA.jar
                    │           ├── json-schema-validator-0.0.1-SNAPSHOT.jar
                    │           ├── json-schema-validator-0.0.1-SNAPSHOT.jar.pack.gz
                    │           ├── json-schema-validator-0.1.6.l7p1.jar
                    │           ├── kerb-client-1.0.0-RC2.jar
                    │           ├── kerb-client-api-all-1.0.0-RC2.jar
                    │           ├── kerb-common-1.0.0-RC2.jar
                    │           ├── kerb-core-1.0.0-RC2.jar
                    │           ├── kerb-crypto-1.0.0-RC2.jar
                    │           ├── kerb-util-1.0.0-RC2.jar
                    │           ├── kerby-asn1-1.0.0-RC2.jar
                    │           ├── kerby-config-1.0.0-RC2.jar
                    │           ├── kerby-pkix-1.0.0-RC2.jar
                    │           ├── kerby-util-1.0.0-RC2.jar
                    │           ├── kunststoff-2.0.2.jar
                    │           ├── kunststoff-2.0.2.jar.pack.gz
                    │           ├── layer7-uddi-lib-1.1.0.jar
                    │           ├── layer7-uddi-lib-1.1.0.jar.pack.gz
                    │           ├── log4j-over-slf4j-1.6.6.jar
                    │           ├── log4j-over-slf4j-1.6.6.jar.pack.gz
                    │           ├── looks-1.1.3.jar
                    │           ├── looks-1.1.3.jar.pack.gz
                    │           ├── mail-1.6.1.jar
                    │           ├── mail-1.6.1.jar.pack.gz
                    │           ├── mina-core-2.0.7.jar
                    │           ├── mockwebserver-20130505.jar
                    │           ├── nekohtml-1.9.15.jar
                    │           ├── nekohtml-1.9.15.jar.pack.gz
                    │           ├── ntlmv2-lib-1.0.4.jar
                    │           ├── persistence-api-2.0.0.jar
                    │           ├── persistence-api-2.0.0.jar.pack.gz
                    │           ├── policy-1.0.jar
                    │           ├── policy-1.0.jar.pack.gz
                    │           ├── quartz-2.2.1.jar
                    │           ├── rsyntaxtextarea-2.0.6.jar
                    │           ├── saxon9ee-9.4.0.9.jar
                    │           ├── servlet-api-resources-2.5.jar
                    │           ├── sftp-8.8.1.jar
                    │           ├── sftp-8.8.1.jar.pack.gz
                    │           ├── slf4j-api-1.6.6.jar
                    │           ├── slf4j-api-1.6.6.jar.pack.gz
                    │           ├── slf4j-ext-1.6.5.jar
                    │           ├── slf4j-jdk14-1.6.6.jar
                    │           ├── slf4j-jdk14-1.6.6.jar.pack.gz
                    │           ├── smjavaagentapi-12.52.jar
                    │           ├── SmJavaApi-12.52.jar
                    │           ├── smjavasdk2-12.52.jar
                    │           ├── spring-aop-3.0.7.RELEASE.jar
                    │           ├── spring-aop-3.0.7.RELEASE.jar.pack.gz
                    │           ├── spring-asm-3.0.7.RELEASE.jar
                    │           ├── spring-asm-3.0.7.RELEASE.jar.pack.gz
                    │           ├── spring-beans-3.0.7.RELEASE.jar
                    │           ├── spring-beans-3.0.7.RELEASE.jar.pack.gz
                    │           ├── spring-context-3.0.7.RELEASE.jar
                    │           ├── spring-context-3.0.7.RELEASE.jar.pack.gz
                    │           ├── spring-core-3.0.7.RELEASE.jar
                    │           ├── spring-core-3.0.7.RELEASE.jar.pack.gz
                    │           ├── spring-expression-3.0.7.RELEASE.jar
                    │           ├── spring-expression-3.0.7.RELEASE.jar.pack.gz
                    │           ├── spring-jdbc-3.0.7.RELEASE.jar
                    │           ├── spring-jdbc-3.0.7.RELEASE.jar.pack.gz
                    │           ├── spring-orm-3.0.7.RELEASE.jar
                    │           ├── spring-orm-3.0.7.RELEASE.jar.pack.gz
                    │           ├── spring-tx-3.0.7.RELEASE.jar
                    │           ├── spring-tx-3.0.7.RELEASE.jar.pack.gz
                    │           ├── spring-web-3.0.7.RELEASE.jar
                    │           ├── spring-web-3.0.7.RELEASE.jar.pack.gz
                    │           ├── stax-ex-1.2.jar
                    │           ├── stax-ex-1.2.jar.pack.gz
                    │           ├── streambuffer-0.8.jar
                    │           ├── streambuffer-0.8.jar.pack.gz
                    │           ├── validation-api-1.0.0.GA.jar
                    │           ├── validation-api-1.0.0.GA.jar.pack.gz
                    │           ├── whirlycache-1.0.1-l7p1.jar
                    │           ├── whirlycache-1.0.1-l7p1.jar.pack.gz
                    │           ├── wiseman-client-1.0-l7p1.jar
                    │           ├── wiseman-core-1.0.jar
                    │           ├── wsdl4j-1.6.2-l7p3.jar
                    │           ├── wsdl4j-1.6.2-l7p3.jar.pack.gz
                    │           ├── xalan-2.7.2-l7p1.jar
                    │           ├── xalan-2.7.2-l7p1.jar.pack.gz
                    │           ├── xalan-serializer-2.7.2.jar
                    │           ├── xalan-serializer-2.7.2.jar.pack.gz
                    │           ├── xbean-saml-1.1-1.0.jar
                    │           ├── xbean-saml-1.1-1.0.jar.pack.gz
                    │           ├── xbean-saml-2.0-1.0.jar
                    │           ├── xbean-saml-2.0-1.0.jar.pack.gz
                    │           ├── xbean-xenc-xmldsig-1.0.jar
                    │           ├── xbean-xenc-xmldsig-1.0.jar.pack.gz
                    │           ├── xercesImpl-2.11.0-l7p1.jar
                    │           ├── xercesImpl-2.11.0-l7p1.jar.pack.gz
                    │           ├── xml-apis-1.4.01.jar
                    │           ├── xml-apis-1.4.01.jar.pack.gz
                    │           ├── xmlbeans-2.5.0.jar
                    │           ├── xmlbeans-2.5.0.jar.pack.gz
                    │           ├── xmlpad-3.7.jar
                    │           ├── xmlpad-3.7.jar.pack.gz
                    │           ├── xmlpad-res-3.7.jar
                    │           ├── xmlpad-res-3.7.jar.pack.gz
                    │           ├── xmlsec-1.5.7.jar
                    │           ├── xmlsec-1.5.7.jar.pack.gz
                    │           ├── xom-1.2.8.jar
                    │           ├── xom-1.2.8.jar.pack.gz
                    │           ├── xss4j.00.patch-1.1.jar
                    │           ├── xss4j.00.patch-1.1.jar.pack.gz
                    │           ├── xss4j-1.0.jar
                    │           └── xss4j-1.0.jar.pack.gz
                    ├── webstart
                    │   ├── lib
                    │   │   ├── annotations-java8-2016.2.5.jar
                    │   │   ├── antlr-2.7.7-l7p1.jar
                    │   │   ├── aopalliance-1.0.jar
                    │   │   ├── apacheds-i18n-2.0.0-M21.jar
                    │   │   ├── apacheds-kerberos-codec-2.0.0-M21.jar
                    │   │   ├── apache-harmony-asn1-0.1.jar
                    │   │   ├── api-asn1-api-1.0.0-M33.jar
                    │   │   ├── api-asn1-ber-1.0.0-M33.jar
                    │   │   ├── api-i18n-1.0.0-M33.jar
                    │   │   ├── api-ldap-model-1.0.0-M33.jar
                    │   │   ├── api-util-1.0.0-M33.jar
                    │   │   ├── bcpkix-jdk15on-1.60.jar
                    │   │   ├── bcprov-unsigned-jdk15on-1.60.jar
                    │   │   ├── browser-launcher-1.0rc4.jar
                    │   │   ├── commons-codec-1.6.jar
                    │   │   ├── commons-collections-3.2.2.jar
                    │   │   ├── commons-compress-1.10.jar
                    │   │   ├── commons-lang-2.6.jar
                    │   │   ├── commons-lang3-3.2.1.jar
                    │   │   ├── commons-pool-1.6.jar
                    │   │   ├── concurrent-1.3.4.jar
                    │   │   ├── dom4j-1.6.1.jar
                    │   │   ├── ehcache-2.10.3.jar
                    │   │   ├── forms_rt-2016.2.5.jar
                    │   │   ├── hibernate-core-3.6.9.Final.jar
                    │   │   ├── httpclient-4.2.5.jar
                    │   │   ├── httpcore-4.2.4.jar
                    │   │   ├── httpmime-4.2.5.jar
                    │   │   ├── jaaslounge-decoding-2.0-l7p3-SNAPSHOT.jar
                    │   │   ├── jackson-annotations-2.8.6.jar
                    │   │   ├── jackson-core-2.8.6.jar
                    │   │   ├── jackson-core-asl-1.9.7.jar
                    │   │   ├── jackson-databind-2.8.6.jar
                    │   │   ├── jackson-mapper-asl-1.9.7.jar
                    │   │   ├── javax.servlet-api-3.0.1.jar
                    │   │   ├── jaxb-api-2.1.jar
                    │   │   ├── jaxb-impl-2.1.13.jar
                    │   │   ├── jaxen-1.1.4.jar
                    │   │   ├── jaxws-api-2.1.jar
                    │   │   ├── jaxws-rt-2.1.7.jar
                    │   │   ├── jbosscache-core-3.2.5.GA.jar
                    │   │   ├── jboss-common-core-2.2.14.GA.jar
                    │   │   ├── jboss-j2ee-4.0.5.GA.jar
                    │   │   ├── jboss-logging-spi-2.0.5.GA.jar
                    │   │   ├── jcalendar-1.4.jar
                    │   │   ├── jcifs-1.3.17.jar
                    │   │   ├── jcip-annotations-1.0.jar
                    │   │   ├── jcl-over-slf4j-1.6.6.jar
                    │   │   ├── jcommon-1.0.17.jar
                    │   │   ├── jdom-1.1.3.jar
                    │   │   ├── jfreechart-1.0.14.jar
                    │   │   ├── jgroups-2.6.15.GA.jar
                    │   │   ├── json-schema-validator-0.0.1-SNAPSHOT.jar
                    │   │   ├── json-schema-validator-0.1.6.l7p1.jar
                    │   │   ├── kerb-client-1.0.0-RC2.jar
                    │   │   ├── kerb-client-api-all-1.0.0-RC2.jar
                    │   │   ├── kerb-common-1.0.0-RC2.jar
                    │   │   ├── kerb-core-1.0.0-RC2.jar
                    │   │   ├── kerb-crypto-1.0.0-RC2.jar
                    │   │   ├── kerb-util-1.0.0-RC2.jar
                    │   │   ├── kerby-asn1-1.0.0-RC2.jar
                    │   │   ├── kerby-config-1.0.0-RC2.jar
                    │   │   ├── kerby-pkix-1.0.0-RC2.jar
                    │   │   ├── kerby-util-1.0.0-RC2.jar
                    │   │   ├── kunststoff-2.0.2.jar
                    │   │   ├── layer7-uddi-lib-1.1.0.jar
                    │   │   ├── log4j-over-slf4j-1.6.6.jar
                    │   │   ├── looks-1.1.3.jar
                    │   │   ├── mail-1.6.1.jar
                    │   │   ├── manager.jar
                    │   │   ├── mina-core-2.0.7.jar
                    │   │   ├── mockwebserver-20130505.jar
                    │   │   ├── nekohtml-1.9.15.jar
                    │   │   ├── ntlmv2-lib-1.0.4.jar
                    │   │   ├── persistence-api-2.0.0.jar
                    │   │   ├── policy-1.0.jar
                    │   │   ├── quartz-2.2.1.jar
                    │   │   ├── rsyntaxtextarea-2.0.6.jar
                    │   │   ├── saxon9ee-9.4.0.9.jar
                    │   │   ├── servlet-api-resources-2.5.jar
                    │   │   ├── sftp-8.8.1.jar
                    │   │   ├── slf4j-api-1.6.6.jar
                    │   │   ├── slf4j-ext-1.6.5.jar
                    │   │   ├── slf4j-jdk14-1.6.6.jar
                    │   │   ├── spring-aop-3.0.7.RELEASE.jar
                    │   │   ├── spring-asm-3.0.7.RELEASE.jar
                    │   │   ├── spring-beans-3.0.7.RELEASE.jar
                    │   │   ├── spring-context-3.0.7.RELEASE.jar
                    │   │   ├── spring-core-3.0.7.RELEASE.jar
                    │   │   ├── spring-expression-3.0.7.RELEASE.jar
                    │   │   ├── spring-jdbc-3.0.7.RELEASE.jar
                    │   │   ├── spring-orm-3.0.7.RELEASE.jar
                    │   │   ├── spring-tx-3.0.7.RELEASE.jar
                    │   │   ├── spring-web-3.0.7.RELEASE.jar
                    │   │   ├── stax-ex-1.2.jar
                    │   │   ├── streambuffer-0.8.jar
                    │   │   ├── validation-api-1.0.0.GA.jar
                    │   │   ├── version.xml
                    │   │   ├── whirlycache-1.0.1-l7p1.jar
                    │   │   ├── wiseman-client-1.0-l7p1.jar
                    │   │   ├── wiseman-core-1.0.jar
                    │   │   ├── wsdl4j-1.6.2-l7p3.jar
                    │   │   ├── xalan-2.7.2-l7p1.jar
                    │   │   ├── xalan-serializer-2.7.2.jar
                    │   │   ├── xbean-saml-1.1-1.0.jar
                    │   │   ├── xbean-saml-2.0-1.0.jar
                    │   │   ├── xbean-xenc-xmldsig-1.0.jar
                    │   │   ├── xercesImpl-2.11.0-l7p1.jar
                    │   │   ├── xml-apis-1.4.01.jar
                    │   │   ├── xmlbeans-2.5.0.jar
                    │   │   ├── xmlpad-3.7.jar
                    │   │   ├── xmlpad-res-3.7.jar
                    │   │   ├── xmlsec-1.5.7.jar
                    │   │   ├── xom-1.2.8.jar
                    │   │   ├── xss4j.00.patch-1.1.jar
                    │   │   └── xss4j-1.0.jar
                    │   ├── manager.jnlp
                    │   └── resources
                    │       ├── ca_logo_black_16x16.jpg
                    │       ├── ca_logo_black_32x32.jpg
                    │       └── ca_logo_black_64x64.jpg
                    └── wsil2xhtml.xml

# portal 9.4

/opt/apim-portal-4.2.9.3-final
├── certs
│   ├── analytics.crt
│   ├── analytics.p12
│   ├── analytics.p8
│   ├── apim.crt
│   ├── apim.p12
│   ├── apim.p8
│   ├── apim.pem
│   ├── datalake.p12
│   ├── dispatcher.p12
│   ├── dssg.p12
│   ├── pssg.p12
│   ├── smtp-internal.crt
│   ├── smtp-internal.key
│   ├── smtp-internal.pem
│   ├── solr.crt
│   ├── solr.p12
│   ├── solr.p8
│   ├── tps.crt
│   ├── tps.p12
│   ├── tps.p8
│   └── tssg.p12
├── conf
│   ├── portal.conf
│   └── portal.conf.sample
├── config.sh -> portal.sh
├── portal.sh
├── status.sh
└── util
    ├── configure-node.sh
    ├── create-tenant.sh
    ├── db-backup.sh
    ├── db-restore.sh
    ├── db-upgrade
    │   ├── common-changelogs
    │   │   ├── common-10.0
    │   │   │   ├── common-10.0-changelog.xml
    │   │   │   ├── de287059-modified-oauth-scope-datatype
    │   │   │   │   └── portaldb-10.0-sprint4-ddl-DE287059-changelog.xml
    │   │   │   ├── org-api
    │   │   │   │   ├── portaldb-10.0-sprint1-ddl-api-catalog-view-changelog.xml
    │   │   │   │   ├── portaldb-10.0-sprint1-ddl-api-extended-view-changelog.xml
    │   │   │   │   ├── portaldb-10.0-sprint1-ddl-api-view-changelog.xml
    │   │   │   │   ├── portaldb-10.0-sprint1-ddl-organization-api-view-changelog.xml
    │   │   │   │   └── portaldb-10.0-sprint1-ddl-org-api-changelog.xml
    │   │   │   ├── org-role
    │   │   │   │   └── portaldb-10.0-sprint3-ddl-user-org-role-changelog.xml
    │   │   │   └── policy-builder
    │   │   │       ├── portaldb-10.0_sprint1-DDL-API_POLICY_ENTITY_XREF-changelog.xml
    │   │   │       ├── portaldb-10.0_sprint2-DDL-API_POLICY_ENTITY_XREF-changelog.xml
    │   │   │       ├── portaldb-10.0_sprint3-DDL-API_EXTENDED_VIEW-changelog.xml
    │   │   │       ├── portaldb-10.0_sprint3-DDL-API_POLICY_TEMPLATE_XREF-changelog.xml
    │   │   │       ├── portaldb-10.0_sprint4-DDL-API_EXTENDED_VIEW-orgid-merge-changelog.xml
    │   │   │       ├── portaldb-10.0_sprint4-DDL-API_POLICY_TEMPLATE_XREF_VIEW-changelog.xml
    │   │   │       ├── portaldb-10.0_sprint4-DDL-API_VIEW-orgid-merge-changelog.xml
    │   │   │       └── portaldb-10.0_sprint5-DDL-API_POLICY_TEMPLATE_XREF_VIEW-changelog.xml
    │   │   ├── common-11.0
    │   │   │   ├── api-rocket-fuel
    │   │   │   │   ├── portaldb-11.0-sprint5-ddl-api-proxy-state-view-rocket-fuel.xml
    │   │   │   │   └── portaldb-11.0-sprint5-ddl-api-view-api-rocket-fuel.xml
    │   │   │   ├── common-11.0-changelog.xml
    │   │   │   ├── sprint03
    │   │   │   │   └── tenantdb-11.0-sprint3-api-view-perf.xml
    │   │   │   ├── swagger-updates
    │   │   │   │   └── portaldb-11.0-sprint2-ddl-api-spec-content-changelog.xml
    │   │   │   └── update-api-view
    │   │   │       └── portaldb-11.0-sprint4-ddl-api-view-changelog.xml
    │   │   ├── common-12.0
    │   │   │   ├── common-12.0-changelog.xml
    │   │   │   ├── devconsole
    │   │   │   │   └── portaldb-12.0-sprint2-DDL-add-apim-platform.xml
    │   │   │   └── tenant-gateway
    │   │   │       └── portaldb-12.0-sprint1-ddl-tenant-gateway.xml
    │   │   ├── common-13.0
    │   │   │   ├── analytics
    │   │   │   │   └── portaldb-13.0-sprint3-ddl-add-rta-enabled-boolean.xml
    │   │   │   └── common-13.0-changelog.xml
    │   │   ├── common-7.0
    │   │   │   ├── common-7.0-changelog.xml
    │   │   │   ├── common-7.0-new-dashboard-changelog.xml
    │   │   │   └── sprint03
    │   │   │       └── tenantdb-7.0-sprint03-DML-new-dashboard-changelog.xml
    │   │   ├── common-8.0
    │   │   │   ├── common-8.0-changelog.xml
    │   │   │   ├── sprint01
    │   │   │   │   └── tenantdb-8.0-sprint01-DML-fix-dashboard-url-changelog.xml
    │   │   │   ├── sprint02
    │   │   │   │   └── portaldb-8.0-sprint2-DDL-add-cms-saml-url.xml
    │   │   │   └── sprint03
    │   │   │       └── tenantdb-8.0-sprint03-solr.xml
    │   │   ├── common-9.0
    │   │   │   ├── common-9.0-changelog.xml
    │   │   │   └── sprint01
    │   │   │       └── portaldb-9.0_sprint1-DDL-TENANT_INFO_TRIALS-changelog.xml
    │   │   └── common-master-changelog.xml
    │   ├── db-upgrade.sh
    │   ├── liquibase-3.2.2.jar
    │   ├── mariadb-java-client-2.2.0.jar
    │   ├── otk-changelogs
    │   │   ├── baseline
    │   │   │   ├── otk-3.2.00-DML1-changelog.xml
    │   │   │   ├── otk-3.2-baseline-data.xml
    │   │   │   ├── otk-3.2-baseline.xml
    │   │   │   └── otk-3.2-changelog.xml
    │   │   ├── otk-3.4
    │   │   │   ├── otk-3.4-changelog.xml
    │   │   │   ├── otkdb-3.4.00-DDL1-changelog.xml
    │   │   │   ├── otkdb-3.4.00-DDL2-changelog.xml
    │   │   │   ├── otkdb-3.4.00-DDL3-changelog.xml
    │   │   │   └── otkdb-3.4.00-DML1-changelog.xml
    │   │   ├── otk-3.5.01
    │   │   │   ├── otk-3.5.01-changelog.xml
    │   │   │   ├── otkdb-3.5.01-DDL1-changelog.xml
    │   │   │   └── otkdb-3.5.01-DML1-changelog.xml
    │   │   ├── otk-3.6.00
    │   │   │   ├── otk-3.6.00-changelog.xml
    │   │   │   └── otkdb-3.6.00-DML1-changelog.xml
    │   │   ├── otk-4.0.00
    │   │   │   ├── otk-4.0.00-changelog.xml
    │   │   │   ├── otkdb-4.0.00-DDL1-changelog.xml
    │   │   │   ├── otkdb-4.0.00-DDL2-changelog.xml
    │   │   │   └── otkdb-4.0.00-DML1-changelog.xml
    │   │   ├── otk-baseline-changelog.xml
    │   │   ├── otkdb-upgrade-changelog.xml
    │   │   └── otk-master-changelog.xml
    │   └── portaldb-changelogs
    │       ├── changesets
    │       │   ├── api
    │       │   │   └── portaldb-12.0-spring4-ddl-spec-content-changelog.xml
    │       │   ├── apirf
    │       │   │   └── portaldb-12.0-sprin3-ddl-api-view-perf.xml
    │       │   ├── branding
    │       │   │   ├── portaldb-12.0-sprint2-DDL-Create-Theme-Table.xml
    │       │   │   ├── portaldb-12.0-sprint2-DML-Adding-Default-Theme-Table.xml
    │       │   │   └── portaldb-13.0-sprint1-DML-Update-Default-Theme-Table.xml
    │       │   ├── devconsole
    │       │   │   └── portaldb-13.0-sprint1-delete-devconsole-app-changelog.xml
    │       │   ├── federatedDeployment
    │       │   │   ├── federated-deployment-common.xml
    │       │   │   ├── portal-db-13.1-sprint1-ddl-api-tenant-gateway.xml
    │       │   │   ├── portal-db-13.1-sprint1-ddl-api-view.xml
    │       │   │   └── portal-db-13.1-sprint1-ddl-api.xml
    │       │   ├── orgpirf
    │       │   │   └── portaldb-12.0-sprin4-ddl-org-view-perf.xml
    │       │   ├── serviceRegistry
    │       │   │   ├── portaldb-12.0-sprint3-servicenav.xml
    │       │   │   ├── portaldb-13.0-sprint1-servicenav-default-data.xml
    │       │   │   ├── portaldb-13.0-sprint4.1-deniedservicenavtorole-default-data.xml
    │       │   │   ├── portaldb-13.0-sprint4.1-deniedservicetorole-default-data.xml
    │       │   │   ├── portaldb-13.0-sprint4-deniedservicenavtorole.xml
    │       │   │   ├── portaldb-13.0-sprint4-deniedservicetorole.xml
    │       │   │   ├── portaldb-13.0-sprint4-service-edit-default-data.xml
    │       │   │   ├── portaldb-13.0-sprint4-servicenav-default-dev-apps.xml
    │       │   │   ├── portaldb-13.0-sprint4-servicenav-default-usernav.xml
    │       │   │   ├── portaldb-13.0-sprint5-add-portal-api-and-cms-services.xml
    │       │   │   ├── portaldb-13.0-sprint5-analytics-update.xml
    │       │   │   ├── portaldb-13.0-sprint5-servicelink-update.xml
    │       │   │   ├── portaldb-13.0-sprint5-service-update-setting-page.xml
    │       │   │   └── portaldb-13.0-sprint5-update-apim-platform-setting.xml
    │       │   ├── token
    │       │   │   └── portaldb-12.0-sprint3-ddl-TOKEN_INDEX.xml
    │       │   └── user_info
    │       │       └── portaldb-13.0-sprint1-ddl-USER_INFO.xml
    │       ├── portaldb-1.2
    │       │   ├── baseline-1.2
    │       │   │   ├── portaldb-1.2-DDL-changelog.xml
    │       │   │   └── portaldb-1.2-DML-changelog.xml
    │       │   └── portaldb-1.2-changelog.xml
    │       ├── portaldb-12.0
    │       │   ├── portaldb-12.0-changelog.xml
    │       │   ├── sprint02
    │       │   │   └── portaldb-12.0-sprint2-ddl-tenant-gateway-auto-deploy.xml
    │       │   └── sprint04
    │       │       └── portaldb-12.0-sprint4-ddl-group-changelog.xml
    │       ├── portaldb-1.3
    │       │   ├── portaldb-1.3-changelog.xml
    │       │   ├── sprint00-04
    │       │   │   ├── portaldb-1_3-sprint00-04-DDL-changelog.xml
    │       │   │   └── portaldb-1_3-sprint00-04-DML-changelog.xml
    │       │   ├── sprint05
    │       │   │   ├── portaldb-1_3-sprint05-DDL-changelog.xml
    │       │   │   └── portaldb-1_3-sprint05-DML-changelog.xml
    │       │   └── sprint08
    │       │       ├── portaldb-1_3-sprint08-DDL-changelog.xml
    │       │       └── portaldb-1_3-sprint08-DML-changelog.xml
    │       ├── portaldb-13.0
    │       │   ├── portaldb-13.0-changelog.xml
    │       │   ├── sprint01
    │       │   │   └── portaldb-13.0-sprint1-ddl-api-group-changelog.xml
    │       │   ├── sprint03
    │       │   │   └── portaldb-13.0-sprint3-ddl-api-group-assoc-cascade-delete.xml
    │       │   ├── sprint04
    │       │   │   └── portaldb-13.0-sprint4-ddl-organization-all-api-view.xml
    │       │   └── sprint05
    │       │       ├── portaldb-13.0-sprint5-ddl-tenant-gateway-add-deployment-type.xml
    │       │       └── portaldb-13.0-sprint5-dml-setting-remove-api-groups-feature-flag.xml
    │       ├── portaldb-1.4
    │       │   ├── portaldb-1.4-changelog.xml
    │       │   └── sprint01
    │       │       ├── portaldb-1_4-sprint01-DDL-changelog.xml
    │       │       └── portaldb-1_4-sprint01-DML-changelog.xml
    │       ├── portaldb-2.1
    │       │   ├── portaldb-2.1-changelog.xml
    │       │   ├── sprint04
    │       │   │   ├── portaldb-2_1-sprint04-DDL-changelog.xml
    │       │   │   └── portaldb-2_1-sprint04-DML-changelog.xml
    │       │   └── sprint05
    │       │       ├── portaldb-2_1-sprint05-DDL-changelog.xml
    │       │       ├── portaldb-2_1-sprint05-DML-changelog.xml
    │       │       ├── portaldb-2_1-sprint05_hybrid_sprint1-DDL-changelog.xml
    │       │       └── portaldb-2_1-sprint05_hybrid_sprint1-DML-changelog.xml
    │       ├── portaldb-2.2
    │       │   ├── 010-hybrid-sprint04
    │       │   │   ├── portaldb-2_2-hybrid_sprint4-DDL-changelog.xml
    │       │   │   └── portaldb-2_2-hybrid_sprint4-DML-changelog.xml
    │       │   ├── 011-hybrid-sprint1.4
    │       │   │   └── portaldb-2_2-hybrid_sprint1.4-DDL-changelog.xml
    │       │   └── portaldb-2.2-changelog.xml
    │       ├── portaldb-3.0
    │       │   ├── portaldb-3.0-changelog.xml
    │       │   └── sprint2.3
    │       │       ├── portaldb-3_0_sprint2.3-DDL-changelog.xml
    │       │       └── portaldb-3_0_sprint2.3-DML-changelog.xml
    │       ├── portaldb-3.1
    │       │   ├── portaldb-3.1-changelog.xml
    │       │   ├── sprint1
    │       │   │   ├── portaldb-3_1_sprint1-DDL-changelog.xml
    │       │   │   └── portaldb-3_1_sprint1-DML-changelog.xml
    │       │   └── sprint2
    │       │       └── portaldb-3_1_sprint2-DDL-changelog.xml
    │       ├── portaldb-6.0
    │       │   ├── portaldb-6.0-changelog.xml
    │       │   └── sprint2
    │       │       └── portaldb-6.0_sprint2-DDL-TENANT_INFO_REFACTORING-changelog.xml
    │       ├── portaldb-7.0
    │       │   ├── portaldb-7.0-changelog.xml
    │       │   ├── sprint1
    │       │   │   ├── portaldb-7.0_sprint1-DDL-TENANT_INFO_MULTICLUSTER-changelog.xml
    │       │   │   ├── portaldb-7.0_sprint1-DML-UPDATE-MULTICLUSTER-FOR-SAAS-changelog.xml
    │       │   │   └── portaldb-7.0-sprint1-ephemeral-pssg-switch.xml
    │       │   └── sprint3
    │       │       ├── tenantdb-7.0-sprint3-ephemeral-pssg-01-tenant-schema.xml
    │       │       └── tenantdb-7.0-sprint3-ephemeral-pssg-02-create-tenant-views.xml
    │       ├── portaldb-8.0
    │       │   ├── portaldb-8.0-changelog.xml
    │       │   └── sprint04
    │       │       └── tenantdb-8.0-sprint4-api-sync-multi-tenant.xml
    │       ├── portaldb-baseline-changelog.xml
    │       ├── portaldb-functions-changelog.xml
    │       ├── portaldb-master-changelog.xml
    │       └── upgrade-changelog.xml
    ├── get-docker.sh
    ├── logfilter
    ├── retrieve-logs.sh
    ├── tenant_info
    └── update-dispatcher.sh

</pre>
