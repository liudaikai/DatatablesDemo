
    <module>dubbo-api</module>
    <module>dubbo-provider</module>
    <module>dubbo-consumer</module>
    <module>dubbo-consumer2</module>
    
     <modelVersion>4.0.0</modelVersion>
      <groupId>DubboDemo</groupId>
      <artifactId>DubboDemo</artifactId>
      <packaging>pom</packaging>
      <version>1.0-SNAPSHOT</version>
    
    <dependency>
          <groupId>org.apache.zookeeper</groupId>
          <artifactId>zookeeper</artifactId>
          <version>3.4.9</version>
        </dependency>
        <!-- dubbo -->
        <dependency>
          <groupId>com.alibaba</groupId>
          <artifactId>dubbo</artifactId>
          <version>2.6.0</version>
          <exclusions>
            <exclusion>
              <groupId>org.springframework</groupId>
              <artifactId>spring</artifactId>
            </exclusion>
          </exclusions>
        </dependency>
        <dependency>
          <groupId>com.101tec</groupId>
          <artifactId>zkclient</artifactId>
          <version>0.10</version>
        </dependency>
