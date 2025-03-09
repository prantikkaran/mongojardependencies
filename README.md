mvn install:install-file -DgroupId=org.restlet.jee \
    -DartifactId=org.restlet.ext.servlet \
    -Dversion=2.3.0 \
    -Dpackaging=jar \
    -Dfile=/home/prantik/Downloads/org.restlet.ext.servlet-2.3.0.jar


    mvn install:install-file -DgroupId=org.restlet.jee \
    -DartifactId=org.restlet.ext.servlet \
    -Dversion=2.3.0 \
    -Dpackaging=pom \
    -Dfile=/home/prantik/Downloads/org.restlet.ext.servlet-2.3.0.pom

    mvn install:install-file \
  -DgroupId=org.restlet.jee \
  -DartifactId=org.restlet.parent \
  -Dversion=2.3.0 \
  -Dpackaging=pom \
  -Dfile=/home/prantik/Downloads/org.restlet.parent-2.3.0.pom


  3. Disbale googlebigtable
  4. Add <checkstyle.skip>true</checkstyle.skip> in pom.xml
