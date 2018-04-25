# Questions-and-errors

# ahop-schema-publish-dockbook-dsl
Failed to execute goal com.rackspace.cloud.api:olink-maven-plugin:1.2.4:olink (generate-product-wadl) on project usage-schema: Error running XProc: net.sf.saxon.s9api.SaxonApiException: Failed to read input file: /var/lib/jenkins/jobs/Dev/jobs/ahop-schema-publish-dockbook-dsl/workspace/message_samples/usagetest6/widget-explicit-widget-usage-v1-response.json (No such file or directory) -> [Help 1]
[ERROR] 
[ERROR] To see the full stack trace of the errors, re-run Maven with the -e switch.
[ERROR] Re-run Maven using the -X switch to enable full debug logging.
[ERROR] 
[ERROR] For more information about the errors and possible solutions, please read the following articles:



# ahop-schema-release-dsl
[ssh-agent] Stopped.
ERROR: Failed to parse POMs
Sending e-mails to: mario.lopez@rackspace.com richard.sartor@rackspace.com teja.cheruku@rackspace.com
ERROR: Could not connect to SMTP host: localhost, port: 25
javax.mail.MessagingException: Could not connect to SMTP host: localhost, port: 25;

# project s2i
WARNING: Exec Failure: HTTP 403, Status: 403 - User "system:serviceaccount:s2i:default" cannot watch buildconfigs in project "s2i"
WARNING: Exec Failure: HTTP 403, Status: 403 - User "system:serviceaccount:s2i:default" cannot watch configmaps in project "s2i"
SEVERE: Failed to load ConfigMaps: io.fabric8.kubernetes.client.KubernetesClientException: User "system:serviceaccount:s2i:default" cannot watch configmaps in project "s2i"
SEVERE: Failed to load BuildConfigs: io.fabric8.kubernetes.client.KubernetesClientException: User "system:serviceaccount:s2i:default" cannot watch buildconfigs in project "s2i"
WARNING: Exec Failure: HTTP 403, Status: 403 - User "system:serviceaccount:s2i:default" cannot watch secrets in project "s2i"
java.net.ProtocolException: Expected HTTP 101 response but was '403 Forbidden'
SEVERE: Failed to load ConfigMaps: io.fabric8.kubernetes.client.KubernetesClientException: User "system:serviceaccount:s2i:default" cannot watch secerts in project "s2i"

SEVERE: Failed to load BuildConfigs: io.fabric8.kubernetes.client.KubernetesClientException: Failure executing: GET at: https://kubernetes.default.svc/oapi/v1/namespaces/s2i/buildconfigs. Message: Forbidden!Configured service account doesn't have access. Service account may have been revoked. User "system:serviceaccount:s2i:default" cannot list buildconfigs in project "s2i".
io.fabric8.kubernetes.client.KubernetesClientException: Failure executing: GET at: https://kubernetes.default.svc/oapi/v1/namespaces/s2i/buildconfigs. Message: Forbidden!Configured service account doesn't have access. Service account may have been revoked. User "system:serviceaccount:s2i:default" cannot list buildconfigs in project "s2i".
