FROM emreyardimci/sso76-openshift-rhel8:latest

COPY sso-extensions.cli /opt/eap/extensions/

COPY ojdbc8.jar /opt/eap/extensions/ojdbc8.jar

COPY cacerts /etc/pki/ca-trust/extracted/java/cacerts

COPY role_attribute_mapper_policy.jar /opt/eap/standalone/deployments

COPY --chown=185:root  base2 /opt/eap/themes/base2
