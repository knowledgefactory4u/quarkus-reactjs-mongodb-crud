# quarkus-reactjs-mongodb-crud
<img src="https://1.bp.blogspot.com/-nvUEPiroMRU/X4rin_dGPJI/AAAAAAAAAkc/jlCyj9k0tUYR8L7YGRpqm8TVwYSizbhqQCPcBGAYYCw/s1535/userlist.png" >

# Local Environment setup

<div class="github" style="border-color: rgb(233, 236, 239) rgb(233, 236, 239) rgb(233, 236, 239) rgb(58, 131, 181); border-image: initial; border-radius: 0.25rem; border-style: solid; border-width: 1px 1px 1px 0.25rem; box-sizing: border-box; margin-bottom: 1.25rem; margin-top: 1.25rem; overflow-wrap: break-word; padding: 1.25rem;"><p style="background-color: transparent; box-sizing: border-box; color: #212529; margin: 0px;"><span style="font-family: inherit;">Step1: Install JDK 11 -&nbsp;<a href="https://www.oracle.com/java/technologies/downloads/" style="background: transparent; color: #bf8b38; text-decoration-line: none;">click here</a></span></p><p style="background-color: transparent; box-sizing: border-box; color: #212529; margin: 0px;"><span style="font-family: inherit;"><br></span></p><p style="background-color: transparent; box-sizing: border-box; color: #212529; margin: 0px;"><span style="font-family: inherit;">Step2: Install eclipse -&nbsp;<a href="https://www.eclipse.org/downloads/" style="background: transparent; color: #bf8b38; text-decoration-line: none;">click here</a></span></p><p style="background-color: transparent; box-sizing: border-box; color: #212529; margin: 0px;"><span style="font-family: inherit;"><br></span></p><p style="background-color: transparent; box-sizing: border-box; color: #212529; margin: 0px;"><span style="font-family: inherit;">Step3: Install ReactJS -&nbsp;<a href="https://www.pragimtech.com/blog/reactjs/install-reactjs/" style="background: transparent; color: #bf8b38; text-decoration-line: none;">click here</a></span></p><p style="background-color: transparent; box-sizing: border-box; color: #212529; margin: 0px;"><span style="font-family: inherit;"><br></span></p><p style="background-color: transparent; box-sizing: border-box; color: #212529; margin: 0px;"><span style="font-family: inherit;">Step4: Install VS code -&nbsp;<a href="https://code.visualstudio.com/" style="background: transparent; color: #bf8b38; text-decoration-line: none;">click here</a></span></p><p style="background-color: transparent; box-sizing: border-box; color: #212529; margin: 0px;"><span style="font-family: inherit;"><br></span></p><p style="background-color: transparent; box-sizing: border-box; color: #212529; margin: 0px;"><span style="font-family: inherit;">Step5: Download/clone the source code -&nbsp;</span></p><p style="background-color: transparent; box-sizing: border-box; color: #212529; margin: 0px;"><span style="font-family: inherit;"><br></span></p><p style="background-color: transparent; box-sizing: border-box; margin: 0px;"><span style="color: #212529;"><span style="font-family: inherit;">Step6: Install Apache Maven -&nbsp;<a href="https://maven.apache.org/install.html" style="background: transparent; color: #bf8b38; text-decoration-line: none;">click here</a></span></span></p><p style="background-color: transparent; box-sizing: border-box; margin: 0px;"><span style="font-family: inherit;"><br></span></p><p style="background-color: transparent; box-sizing: border-box; margin: 0px;"><span style="font-family: inherit;">Step7: Install MongoDB -&nbsp;<a href="https://www.mongodb.com/try/download/community" style="background: transparent; color: #bf8b38; text-decoration-line: none;">click here</a></span></p><p style="background-color: transparent; box-sizing: border-box; font-family: system-ui, -apple-system, &quot;Segoe UI&quot;, Roboto, &quot;Helvetica Neue&quot;, Arial, &quot;Noto Sans&quot;, &quot;Liberation Sans&quot;, sans-serif, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, &quot;Segoe UI Symbol&quot;, &quot;Noto Color Emoji&quot;; margin: 0px;"><br></p><p style="background-color: transparent; box-sizing: border-box; font-family: system-ui, -apple-system, &quot;Segoe UI&quot;, Roboto, &quot;Helvetica Neue&quot;, Arial, &quot;Noto Sans&quot;, &quot;Liberation Sans&quot;, sans-serif, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, &quot;Segoe UI Symbol&quot;, &quot;Noto Color Emoji&quot;; margin: 0px;"><br></p><h4 style="background-color: transparent; box-sizing: border-box; font-family: system-ui, -apple-system, &quot;Segoe UI&quot;, Roboto, &quot;Helvetica Neue&quot;, Arial, &quot;Noto Sans&quot;, &quot;Liberation Sans&quot;, sans-serif, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, &quot;Segoe UI Symbol&quot;, &quot;Noto Color Emoji&quot;; font-weight: 400; margin: 0px;"><b>Backend setup</b></h4><div style="background-color: transparent;"><b><br></b></div><p style="box-sizing: border-box; margin: 0px;"><span face="system-ui, -apple-system, Segoe UI, Roboto, Helvetica Neue, Arial, Noto Sans, Liberation Sans, sans-serif, Apple Color Emoji, Segoe UI Emoji, Segoe UI Symbol, Noto Color Emoji" style="font-family: inherit;"><span style="background-color: transparent; color: #212529;">Step8: Build application&nbsp; jar file:&nbsp;</span><b><span style="background-color: black; color: white;">mvn clean package</span></b></span></p><p style="background-color: transparent; box-sizing: border-box; color: #212529; margin: 0px;"><span style="font-family: inherit;"><br></span></p><p style="box-sizing: border-box; margin: 0px;"><span style="font-family: inherit;"><span face="system-ui, -apple-system, &quot;Segoe UI&quot;, Roboto, &quot;Helvetica Neue&quot;, Arial, &quot;Noto Sans&quot;, &quot;Liberation Sans&quot;, sans-serif, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, &quot;Segoe UI Symbol&quot;, &quot;Noto Color Emoji&quot;" style="background-color: transparent;"><span style="color: #212529;">Step9:&nbsp;</span></span><span face="system-ui, -apple-system, Segoe UI, Roboto, Helvetica Neue, Arial, Noto Sans, Liberation Sans, sans-serif, Apple Color Emoji, Segoe UI Emoji, Segoe UI Symbol, Noto Color Emoji"><span style="background-color: transparent; color: #212529;">Start the application:&nbsp;</span><b><span style="background-color: black; color: white;">java -jar quarkus-run.jar</span></b></span></span></p><p style="background-color: transparent; box-sizing: border-box; font-family: system-ui, -apple-system, &quot;Segoe UI&quot;, Roboto, &quot;Helvetica Neue&quot;, Arial, &quot;Noto Sans&quot;, &quot;Liberation Sans&quot;, sans-serif, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, &quot;Segoe UI Symbol&quot;, &quot;Noto Color Emoji&quot;; margin: 0px;"><b><span style="background-color: black; color: white;"><br></span></b></p><p style="background-color: transparent; box-sizing: border-box; color: #212529; font-family: system-ui, -apple-system, &quot;Segoe UI&quot;, Roboto, &quot;Helvetica Neue&quot;, Arial, &quot;Noto Sans&quot;, &quot;Liberation Sans&quot;, sans-serif, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, &quot;Segoe UI Symbol&quot;, &quot;Noto Color Emoji&quot;; margin: 0px;"><br></p><h4 style="background-color: transparent; box-sizing: border-box; color: #212529; font-family: system-ui, -apple-system, &quot;Segoe UI&quot;, Roboto, &quot;Helvetica Neue&quot;, Arial, &quot;Noto Sans&quot;, &quot;Liberation Sans&quot;, sans-serif, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, &quot;Segoe UI Symbol&quot;, &quot;Noto Color Emoji&quot;; font-weight: 400; margin: 0px;"><b>Frontend setup</b></h4><div style="background-color: transparent;"><b><br></b></div><p style="box-sizing: border-box; margin: 0px;"><span style="font-family: inherit;"><span face="system-ui, -apple-system, &quot;Segoe UI&quot;, Roboto, &quot;Helvetica Neue&quot;, Arial, &quot;Noto Sans&quot;, &quot;Liberation Sans&quot;, sans-serif, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, &quot;Segoe UI Symbol&quot;, &quot;Noto Color Emoji&quot;" style="background-color: transparent; color: #212529;">Step10:&nbsp;</span><span face="system-ui, -apple-system, Segoe UI, Roboto, Helvetica Neue, Arial, Noto Sans, Liberation Sans, sans-serif, Apple Color Emoji, Segoe UI Emoji, Segoe UI Symbol, Noto Color Emoji"><span style="background-color: transparent; color: #212529;">Download the dependencies using the following command -&nbsp;</span><b><span style="background-color: black; color: white;">npm install</span></b></span></span></p><p style="background-color: transparent; box-sizing: border-box; margin: 0px;"><span face="system-ui, -apple-system, Segoe UI, Roboto, Helvetica Neue, Arial, Noto Sans, Liberation Sans, sans-serif, Apple Color Emoji, Segoe UI Emoji, Segoe UI Symbol, Noto Color Emoji" style="color: #212529; font-family: inherit;"><br></span></p><p style="box-sizing: border-box; margin: 0px;"><span face="system-ui, -apple-system, Segoe UI, Roboto, Helvetica Neue, Arial, Noto Sans, Liberation Sans, sans-serif, Apple Color Emoji, Segoe UI Emoji, Segoe UI Symbol, Noto Color Emoji" style="font-family: inherit;"><span style="color: #212529;">Step11:&nbsp;Run the frontend application -&nbsp;</span><b style="background-color: black;"><span style="color: white;">npm start</span></b></span></p></div>
