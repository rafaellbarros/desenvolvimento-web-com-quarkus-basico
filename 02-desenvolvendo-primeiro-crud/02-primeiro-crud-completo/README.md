# Comandos maven


### Listando extensões do quarkus
```
mvn quarkus:list-extensions
```

### Adicionando uma exstensão
```
mvn quarkus:add-extension -Dextensions="io.quarkus:quarkus-smallrye-openapi"
```

### Adicionando várias extensões
```
mvn quarkus:add-extension -Dextensions="quarkus-hibernate-orm-panache , quarkus-jdbc-mysql, quarkus-resteasy-jsonb"
```