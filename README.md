# basepom-spotless-errorprone-mvn-archetype

A Maven archetype that lets you start with basepom, spotless, errorprone, junit.

## Usage

You might need to clone this project and install it in your local .m2 repository with `mvn clean install`. Then:

```bash
mvn archetype:generate -DarchetypeGroupId=name.seguri.java -DarchetypeArtifactId=basepom-spotless-errorprone-archetype -DarchetypeVersion=1.0.0 -DinteractiveMode=false -DgroupId=com.example -DartifactId=demo -Dversion=1.0-SNAPSHOT
```

