Welcome to Atmosphere, a portable AjaxPush/Comet and WebSocket Framework for everyone. The framework support the majority of existing Webserver, and our JQuery Plugin support WebSocket (when available) and Comet (Http Streaming and long Polling)

Atmosphere is a POJO based framework using Inversion of Control (IoC) to bring push/Comet to the masses! Finally a framework which can run on any Java based Web Server, including Google App Engine, Tomcat, Jetty, GlassFish, Weblogic, Grizzly, JBossWeb and JBoss, Resin, etc. without having to wait for Servlet 3.0 Async support or without the needs to learn how Comet or WebSocket support has been differently implemented by all those Containers.  

Servlet 3.0 is supported along with framework like Jersey (natively), GWT (natively), Wicket, Guice, Spring etc. and programming language like JRuby, Groovy and Scala. We also support massive scalability with our Cluster plugin architecture (JGroups, JMS/ActiveMQ, Redis, XMPP,i etc.).

Read about why you should use Atmosphere instead of Servlet 3.0 Async

     http://jfarcand.wordpress.com/2009/11/06/servlet-3-0-asynchronous-api-or-atmosphere-easy-decision/

Atmosphere is also availaible as part of the following framework:

* The Atmosphere Grails Plug In
* Java Server Face via PrimeFaces
* Akka, event-driven, scalable and fault-tolerant architectures for the JVM

Atmosphere ship with a JQuery Plug In that can be used with any Comet or WebSocket Framework:

    http://is.gd/bJXhH

Download Atmosphere Whitepaper

    https://atmosphere.dev.java.net/atmosphere_whitepaper.pdf

If you are using Maven, just add the following dependency:

    <dependency>
         <groupId>org.atmosphere</groupId>
         <artifactId>atmosphere-{atmosphere-module]</artifactId>
         <version>0.7.0</version>
     </dependency>

Where atmosphere-module can be: jersey, runtime, guice, bayeux, cluster or spade-server. Our official release are available from Maven Central. For SNAPSHOT, you'll have to add the Sonatype repo to your settings in order to be able to access the snapshot builds:

    http://oss.sonatype.org/service/local/repositories/snapshots/content

Atmosphere 0.7.0 is our official release, and our work in progress version is 0.8, targeted for end of April

If you are interested, subscribe to our mailing lists (user@atmosphere.dev.java.net or dev@atmosphere.dev.java.net) for more info!  We are on irc.freenode.net under #atmosphere-comet
