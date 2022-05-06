![image](https://user-images.githubusercontent.com/66588814/167067134-57c1609a-2f99-440b-b792-ea1a760b038c.png)

### Q - What is POM 
==> Project Oriented Model

### Minimum Requirement for POM 

- **Project** - root
- **Model Version** - 4.0.0
- **group id** - com
- **artifact** - vdoxx
- **version** - 2.1
- **Packaging** - war   

### Sample 

```
<project> 
    <model version>4.0.0</model version>
    <group id >com</group id>
    <artifact id>vdoxx</artifact>
    <version>2.1</version>
</project>
```


### Plugin
Plugin | Description
-- | --
Core plugins | Plugins corresponding to default core phases (ie. clean, compile). They may have multiple goals as well.
clean | Clean up after the build.
compiler | Compiles Java sources.
deploy | Deploy the built artifact to the remote repository.
failsafe | Run the JUnit integration tests in an isolated classloader.
install | Install the built artifact into the local repository.
resources | Copy the resources to the output directory for including in the JAR.
site | Generate a site for the current project.
surefire | Run the JUnit unit tests in an isolated classloader.
verifier | Useful for integration tests - verifies the existence of certain conditions.

**_for ex- mvn clean install (it clean the build after installation)_**

### Packaging
Packaging  | Description
-- | --
ear | Generate an EAR from the current project.
ejb | Build an EJB (and optional client) from the current project.
jar | Build a JAR from the current project.
rar |  Build a RAR from the current project.

### Feature of Maven

![image](https://user-images.githubusercontent.com/66588814/167067527-06758ede-8cb7-4b14-8113-ec751a9c9fce.png)

`note: Every maven project has a packaging type, by default its jar `
