JC = javac
JAVA = java/*.java #Donde se encuentran los Javas 
OUT = out/ 
DIR = /home/usuario/Escritorio/Despliegue-main/Bully/war/WEB-INF/lib#Directorio de la librerías

LIB = $(DIR)/aopalliance-repackaged-2.6.1.jar:$(DIR)/hk2-api-2.6.1.jar:$(DIR)/hk2-locator-2.6.1.jar:$(DIR)/hk2-utils-2.6.1.jar:$(DIR)/jakarta.activation-api-1.2.2.jar:$(DIR)/jakarta.annotation-api-1.3.5.jar:$(DIR)/jakarta.inject-2.6.1.jar:$(DIR)/jakarta.json.bind-api-1.0.2.jar:$(DIR)/jakarta.json-1.1.6.jar:$(DIR)/jakarta.json-1.1.6-module.jar:$(DIR)/jakarta.json-api-1.1.6.jar:$(DIR)/jakarta.persistence-api-2.2.3.jar:$(DIR)/jakarta.servlet-api-4.0.3.jar:$(DIR)/jakarta.validation-api-2.0.2.jar:$(DIR)/jakarta.ws.rs-api-2.1.6.jar:$(DIR)/jakarta.ws.rs-api-2.1.6-sources.jar:$(DIR)/jakarta.xml.bind-api-2.3.3.jar:$(DIR)/javassist-3.25.0-GA.jar:$(DIR)/jersey-client.jar:$(DIR)/jersey-common.jar:$(DIR)/jersey-container-servlet.jar:$(DIR)/jersey-container-servlet-core.jar:$(DIR)/jersey-hk2.jar:$(DIR)/jersey-media-jaxb.jar:$(DIR)/jersey-media-json-binding.jar:$(DIR)/jersey-media-sse.jar:$(DIR)/jersey-server.jar:$(DIR)/org.osgi.core-6.0.0.jar:$(DIR)/osgi-resource-locator-1.0.3.jar:$(DIR)/yasson-1.0.9.jar


default: 
	$(JC) -cp $(LIB) $(JAVA) -d $(OUT)

clean : 
	$(RM) *.class
