# boot-jsp-archetype
maven sprring boot jsp web archetype

## usage
### install to local
```bash
mvn clean install
```
### deploy to your private nexus
```bash
mvn deploy
```
### generate project
```bash
mvn archetype:generate -DarchetypeCatalog=local
# inactive mode: input your groupid, artifactId, version, pacage-name and so on....
```