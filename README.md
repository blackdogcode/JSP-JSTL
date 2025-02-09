## 0. Articles
<ul>
  <li><a href="https://stackoverflow.com/questions/101579/when-do-you-use-a-jsp-and-when-a-servlet">When do you use a JSP and when a Servlet? - stack overflow</a></li>
  <li><a href="https://real-world-java-ee.zeef.com/arjan.tijms">Real World Java EE</a></li>
  <li><a href="www.oracle.com/technetwork/java/javaee/tech/index.html">Oracle support JSP Servlet in JAVA EE</a></li>
  <li><a href="https://www.educba.com/jsp-vs-javascript/">Difference Between JSP vs JavaScript</a></li>
  <li><a href="https://stackoverflow.com/questions/3804209/what-are-sessions-how-do-they-work\">What are sessions? How do they work?</a></li>
  <li><a href="http://www.whatarecookies.com/">What is Cookie?</a></li>
  <li><a href="https://en.wikipedia.org/wiki/Single_sign-on">What is Single_sign-on</a></li>
  <li><a href="https://www.quora.com/What-is-the-difference-between-Java-servlets-and-JSP">JSP vs Servlet</a></li>
  <li><a href="https://www.javatpoint.com/MVC-in-jsp">What is MVC in JSP</a></li>
  <li><a href="https://www.geeksforgeeks.org/difference-between-jsp-and-asp/">JSP(for Java Oracle) vs ASP(for .Net Microsoft)</a></li>
</ul>

## 1. References
<ul>
  <li><a href="https://www.javatpoint.com/jsp-tutorial">Java Point - Learn JSP</a></li>
  <li><a href="https://www.javatpoint.com/servlet-tutorial">Java Point - Learn Servlet</a></li>
</ul>

## 2. JSP Introduction
<ol>
  <ul>
    <li><a href="https://www.javatpoint.com/jsp-tutorial">Life Cycle of JSP</a></li>
    <li><a href="https://www.javatpoint.com/jsp-api">JSP APIs</a>
      <ol>
        <li><a href="https://docs.oracle.com/javaee/7/api/javax/servlet/jsp/package-summary.html">javax.servlet.jsp pacakges</a></li>
        <li><a href="https://tomcat.apache.org/tomcat-7.0-doc/jspapi/javax/servlet/jsp/tagext/package-summary.html">javax.servlet.jsp.tagext packages</a></li>
      </ol>
    </li>
    <li><a href="https://www.javatpoint.com/creating-jsp-in-eclipse-ide">JSP in Eclipse</a></li>
  </ul>
</ol>

<kbd>
<img src="https://github.com/Blackdog-Programmer/JSP-Servlet/blob/master/reference/JSP-Fundamentals/JSP-to-Servlet-Transition.png" alt="JSP to Servelet Trasition Process">
</kbd>

## 3. JSP Scripting Elements
<ol>
  <li><a href="https://www.javatpoint.com/jsp-scriptlet-tag">JSP Scriptlet tag</a></li>
    <kbd>
      <img src="https://github.com/Blackdog-Programmer/JSP-Servlet/blob/master/reference/JSP-Fundamentals/jsp_scriplet_tag_syntax.png" alt="jsp scriplet tag syntax">
    </kbd>
  <li><a href="https://www.javatpoint.com/jsp-expression-tag">JSP expression tag</a></li>
    <kbd>  
      <img src="https://github.com/Blackdog-Programmer/JSP-Servlet/blob/master/reference/JSP-Fundamentals/jsp_expression_tag_syntax.png" alt="jsp expression tag syntax">
    </kbd>
  <li><a href="https://www.javatpoint.com/jsp-declaration-tag">JSP Declaration Tag</a></li>
    <kbd> 
      <img src="https://github.com/Blackdog-Programmer/JSP-Servlet/blob/master/reference/JSP-Fundamentals/jsp_declaration_tag_syntax.png" alt="jsp scriplet syntax">
    </kbd>
</ol>

<kbd>
<img src="https://github.com/Blackdog-Programmer/JSP-Servlet/blob/master/reference/JSP-Fundamentals/Diff_JSP_Scriplet_Delcaration_Tag.png", alt="Diff JSP Scriplet and Declaration Tag">
</kbd>

## 4. JSP Implicit Objects

<kbd>
<img src="https://github.com/Blackdog-Programmer/JSP-Servlet/blob/master/reference/Implicit-Objects/JSP_9_Implicit_Objects.png" alt="JSP 9 Implicit Objects">
</kbd>

<ul>
  <li><a href="https://www.javatpoint.com/jsp-implicit-objects">out</a></li>
  <li><a href="https://www.javatpoint.com/request-implicit-object">request</a></li>
  <li><a href="https://www.javatpoint.com/response-implicit-object">response<a></li>
  <li><a href="https://www.javatpoint.com/config-implicit-object">config</a></li>
    Generally, it is used to get initialization parameter from the web.xml file<br><br>
  <li><a href="https://www.javatpoint.com/application-implicit-object">application</a></li>
    This object can be used to get initialization parameter from configuaration file (web.xml).<br>
    It can also be used to get, set or remove attribute from the application scope.<br><br>
  <li><a href="https://www.javatpoint.com/session-implicit-object">session</a></li>
    <a href="https://www.computerhope.com/jargon/s/session.htm">What is Websession</a></li>
    In JSP, session is an implicit object of type HttpSession.<br/>
    The Java developer can use this object to set,get or remove attribute or to get session information.<br><br>
  <li><a href="https://www.javatpoint.com/pageContext-implicit-object">pageContext</a></li>
    In JSP, pageContext is an implicit object of type PageContext class.</br>
    The pageContext object can be used to set,get or remove attribute from 'page', 'request', 'session', 'application'<br>
  <li><a href="https://www.javatpoint.com/page-implicit-object">page</a></li><br>
  <li><a href="https://www.javatpoint.com/exception-implicit-object">exception</a></li>
    In JSP, exception is an implicit object of type java.lang.Throwable class.<br>
    This object can be used to print the exception. But it can only be used in error pages.
</ul>
  
## 5. JSP directives
The <strong>jsp directives</strong> are messages that tells the web container how to translate a JSP page into the corresponding servlet<br>

<kbd>
  <img src="https://github.com/Blackdog-Programmer/JSP-Servlet/blob/master/reference/directives/jsp_directive_syntax.png" alt="jsp directive syntax image">
</kbd><br><br>

<ul>
  <li><a href="https://www.javatpoint.com/jsp-page-directive">page directive</a><br>
    <kbd>
      <img src="https://github.com/Blackdog-Programmer/JSP-Servlet/blob/master/reference/directives/jsp_directive_page_syntax.png" alt="page directive syntax image">
    </kbd><br>
    <ul> 
      <li><strong>import:</strong> The import attribute is used to import class, interface or all the members of a package.</li><br>
      <li><strong>contentType:</strong> The contentType attribute defines the MIME(Multipurpose Internet Mail Extension) type of the HTTP response</li><br>
      <li><strong>extends:</strong> The extends attribute defines the parent class that will be inherited by the generated servlet.It is rarely used.</li><br>
      <li><strong>info:</strong> This attribute simply sets the information of the JSP page which is retrieved later by using getServletInfo() method of Servlet interface.</li><br>
      <li><strong>buffer:</strong> The buffer attribute sets the buffer size in kilobytes to handle output generated by the JSP page.The default size of the buffer is 8Kb.</li><br>
      <li><strong>language:</strong> The language attribute specifies the scripting language used in the JSP page. The default value is "java".</li><br>
      <li><strong>isELIgnored:</strong> We can ignore the Expression Language (EL) in jsp by the isELIgnored attribute. By default its value is false</li><br>
      <li><strong>isThreadSafe:</strong> Servlet and JSP both are multithreaded.If you want to control this behaviour of JSP page, you can use isThreadSafe attribute of page directive</li><br>
      <li><strong>pageEncoding:</strong> </li><br>
      <li><strong>errorPage:</strong> The errorPage attribute is used to define the error page, if exception occurs in the current page, it will be redirected to the error page.</li><br>
      <li><strong>isErrorPage:</strong> The isErrorPage attribute is used to declare that the current page is the error page.</li><br>
    </ul>
  </li>   
  <li><a href="https://www.javatpoint.com/jsp-include-directive">include directive</a></li>
    <kbd>
      <img src="https://github.com/Blackdog-Programmer/JSP-Servlet/blob/master/reference/directives/jsp_directive_include_syntax.png" alt="jsp include directive syntax">
    </kbd><br>
    The include directive is used to include the contents of any resource it may be jsp file, html file or text file.<br><br>
  <li><a href="https://www.javatpoint.com/jsp-taglib-directive">taglib directive</a></li>
    The JSP taglib directive is used to define a tag library that defines many tags.<br>
    <kbd>
      <img src="https://github.com/Blackdog-Programmer/JSP-Servlet/blob/master/reference/directives/jsp_directive_taglib_syntax.png" alt="jsp taglib directive syntax image">
    </kbd>
</ul>

## [6. Exception Handling in JSP](https://www.javatpoint.com/exception-handling-in-jsp)
The exception is normally an object that is thrown at runtime. Exception Handling is the process to handle the runtime errors.<br>
<ol>
  <li>By errorPage and isErrorPage attributes of page directive</li>
  <li>By <error-page> element in web.xml file</li>
</ol>

## 7. JSP Action Tags
The action tags are used to control the flow between <strong>pages</strong> and to use <strong>Java Bean</strong><br>

<kbd>
<img src="https://github.com/Blackdog-Programmer/JSP-Servlet/blob/master/reference/Actions-Tags/jsp-action-tags-list.png" alt="jsp action tags list table image">
</kbd><br><br>

<ul>
  <li><a href="https://www.javatpoint.com/jsp-action-tags-forward-action">jsp:forward</a></li>
  <kbd>
    <img src="https://github.com/Blackdog-Programmer/JSP-Servlet/blob/master/reference/Actions-Tags/jsp-forward-tag-with-parameter-syntax.png" alt="jsp forward action tag syntax image">
  </kbd><br><br>
  
  <li><a href="https://www.javatpoint.com/jsp-include-action">jsp:include action tag</a>
    <ul>
      <li>The jsp:include action tag is used to include the content of another resource it may be jsp, html or servlet.</li>
      <li>The jsp include action tag includes the resource at request time so it is better for dynamic pages because there might be changes in future.</li>
      <li>The jsp:include tag can be used to include static as well as dynamic pages.</li>
    </ul>
  </li><br>
  
  <li><a href="https://www.javatpoint.com/java-bean">Java Bean Class</a><br>
  A JavaBean is a Java class that should follow the following conventions:
    <ul>
      <li>It should have a no-arg constructor.</li>
      <li>It should be Serializable.</li>
      <li>It should provide methods to set and get the values of the properties, known as getter and setter methods.</li>
    </ul>
  </li><br>
  
  <li><a href="https://www.javatpoint.com/jsp-useBean-action">jsp:useBean action tag</a></li>
  <p>The jsp:useBean action tag is used to locate or instantiate a bean class. If bean object of the Bean class is already created, it doesn't create the bean depending on the scope. But if object of bean is not created, it instantiates the bean.</p>
  
  <kbd>
    <img src="https://github.com/Blackdog-Programmer/JSP-Servlet/blob/master/reference/Actions-Tags/jsp-useBean-action-tag-syntax.png" alt="jsp:useBean action tag syntax">
  </kbd><br><br>
  
  <li><a href="https://www.javatpoint.com/jsp-setProperty-and-jsp-getProperty-action-tag">jsp:setProperty and jsp:getProperty</a></li>
  <p>The setProperty and getProperty action tags are used for developing web application with Java Bean. In web devlopment, bean class is mostly used because it is a reusable software component that represents data.</p>
  
  <kbd>
    <img src="https://github.com/Blackdog-Programmer/JSP-JSTL/blob/master/reference/Actions-Tags/jsp-setProperty-action-tag-syntax.png" alt="jsp:setProperty action tag image">
  </kbd><br><br>
  
  <kbd>
    <img src="https://github.com/Blackdog-Programmer/JSP-JSTL/blob/master/reference/Actions-Tags/jsp-getProperty-action-tag-syntax.png" alt="jsp:getProperty action tag image">
  </kbd><br><br>
  
  <li><a href="https://www.javatpoint.com/displaying-applet-in-jsp">Displaying applet in JSP (jsp:plugin action tag)</a></li>
  <p>The jsp:plugin action tag is used to embed applet in the jsp file. The jsp:plugin action tag downloads plugin at client side to execute an applet or bean.</p>
  
  <kbd>
    <img src="https://github.com/Blackdog-Programmer/JSP-JSTL/blob/master/reference/Actions-Tags/jsp-plugin-action-tag-syntax.png" alt="jsp:plugin action tag syntax image">
  </kbd><br><br>
</ul>

## [8. Expression Language (EL) in JSP](https://www.javatpoint.com/EL-expression-in-jsp)
<p>
  The Expression Language (EL) simplifies the accessibility of data stored in the Java Bean component, and other objects like request, session, application etc
</p>

<kbd>
  <img src="https://github.com/Blackdog-Programmer/JSP-Servlet/blob/master/reference/Expression-Language/Expression-Language-Syntax.png" alt="JSP Expression Langue Syntax Image">
  </kbd><br>
<kbd>
  <img src="https://github.com/Blackdog-Programmer/JSP-Servlet/blob/master/reference/Expression-Language/Implicit-Objects-in-Expression-Language.png" alt="JSP Expression Language Objects List">
</kbd>                                                                                                 

## [9. MVC in JSP](https://www.javatpoint.com/MVC-in-jsp)
<p>
  1. <strong>MVC</strong> stands for Model View and Controller. It is a <strong>design pattern</strong> that separates the business logic, presentation logic and data.<br>
  2. <strong>Controller</strong> acts as an interface between View and Model. Controller intercepts all the incoming requests.<br>
  3. <strong>Model</strong> represents the state of the application i.e. data. It can also have business logic.<br>
  4. <strong>View</strong> represents the presentaion i.e. UI(User Interface).
</p>

<kbd>
  <img src="https://github.com/Blackdog-Programmer/JSP-JSTL/blob/master/reference/MVC/MVC_Architecture.png" alt="MVC Architecture">
</kbd><br><br>

## [10. JSTL (JSP Standard Tag Library)](https://www.javatpoint.com/jstl)
<ul>
  <li>Fast Development JSTL provides many tags that simplify the JSP.</li>
  <li>Code Reusability We can use the JSTL tags on various pages.</li>
  <li>No need to use scriptlet tag It avoids the use of scriptlet tag.</li>
</ul>

<kbd>
  <img src="https://github.com/Blackdog-Programmer/JSP-Servlet/blob/master/reference/JSTL/JSTL_5_types_tags_list.png" alt="JSTP 5 tag type list talbe">
</kbd><br><br>

<ul>
  <li><a href="https://mvnrepository.com/artifact/org.glassfish.web/javax.servlet.jsp.jstl/1.2.5">javax.servlet.jsp.jstl-1.2.5.jar</a></li>
  <p>
    This contains the JSTL API interfaces and support classes. However a large number of the interfaces do not have implementation classes.
  </p>

  <li><a href="https://mvnrepository.com/artifact/javax.servlet.jsp.jstl/javax.servlet.jsp.jstl-api/1.2.2">javax.servlet.jsp.jstl-api-1.2.2.jar</a></li>
  <p>This contains an implementation of the JSTL API. This code implements all of the interface from the API above.</p>
</ul>
