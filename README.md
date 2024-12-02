<div class="Box-sc-g0xbh4-0 QkQOb js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font _mstmutation="1" _msttexthash="51598976" _msthash="270">Spring PetClinic 示例应用程序</font><a href="https://github.com/spring-projects/spring-petclinic/actions/workflows/maven-build.yml"><img src="https://github.com/spring-projects/spring-petclinic/actions/workflows/maven-build.yml/badge.svg" alt="构建状态" style="max-width: 100%;" _mstalt="181376" _msthash="268"></a><a href="https://github.com/spring-projects/spring-petclinic/actions/workflows/gradle-build.yml"><img src="https://github.com/spring-projects/spring-petclinic/actions/workflows/gradle-build.yml/badge.svg" alt="构建状态" style="max-width: 100%;" _mstalt="181376" _msthash="269"></a></h1><a id="user-content-spring-petclinic-sample-application-" class="anchor" aria-label="永久链接： Spring PetClinic 示例应用程序" href="#spring-petclinic-sample-application-" _mstaria-label="1534793" _msthash="271"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><a href="https://gitpod.io/#https://github.com/spring-projects/spring-petclinic" rel="nofollow"><img src="https://camo.githubusercontent.com/b04f5659467d23b5109ba935a40c00decd264eea25c22d50a118021349eea94f/68747470733a2f2f676974706f642e696f2f627574746f6e2f6f70656e2d696e2d676974706f642e737667" alt="在 Gitpod 中打开" data-canonical-src="https://gitpod.io/button/open-in-gitpod.svg" style="max-width: 100%;" _mstalt="202085" _msthash="272"></a> <a href="https://github.com/codespaces/new?hide_repo_select=true&amp;ref=main&amp;repo=7517918"><img src="https://github.com/codespaces/badge.svg" alt="在 GitHub Codespaces 中打开" style="max-width: 100%;" _mstalt="507845" _msthash="273"></a></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="75946533" _msthash="274">通过一些图表了解 Spring Petclinic 应用程序</h2><a id="user-content-understanding-the-spring-petclinic-application-with-a-few-diagrams" class="anchor" aria-label="永久链接：通过一些图表了解 Spring Petclinic 应用程序" href="#understanding-the-spring-petclinic-application-with-a-few-diagrams" _mstaria-label="3772145" _msthash="275"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><a href="https://speakerdeck.com/michaelisvy/spring-petclinic-sample-application" rel="nofollow" _msttexthash="35884940" _msthash="276">在此处查看演示文稿</a></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="17357366" _msthash="277">在本地运行 Petclinic</h2><a id="user-content-run-petclinic-locally" class="anchor" aria-label="永久链接：在本地运行 Petclinic" href="#run-petclinic-locally" _mstaria-label="821795" _msthash="278"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="1130767729" _msthash="279">Spring Petclinic 是使用 <a href="https://spring.io/guides/gs/maven/" rel="nofollow" _istranslated="1">Maven</a> 或 <a href="https://spring.io/guides/gs/gradle/" rel="nofollow" _istranslated="1">Gradle</a> 构建的 <a href="https://spring.io/guides/gs/spring-boot" rel="nofollow" _istranslated="1">Spring Boot</a> 应用程序。您可以构建一个 jar 文件并从命令行运行它（它应该与 Java 17 或更高版本一样有效）：</p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>git clone https://github.com/spring-projects/spring-petclinic.git
<span class="pl-c1">cd</span> spring-petclinic
./mvnw package
java -jar target/<span class="pl-k">*</span>.jar</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="git clone https://github.com/spring-projects/spring-petclinic.git
cd spring-petclinic
./mvnw package
java -jar target/*.jar" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto" _msttexthash="69519385" _msthash="280">然后，您可以在 <a href="http://localhost:8080/" rel="nofollow" _istranslated="1">http://localhost:8080/</a> 访问 Petclinic。</p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer nofollow" href="https://cloud.githubusercontent.com/assets/838318/19727082/2aee6d6c-9b8e-11e6-81fe-e889a5ddfded.png"><img width="1042" alt="PETCLINIC-截图" src="https://cloud.githubusercontent.com/assets/838318/19727082/2aee6d6c-9b8e-11e6-81fe-e889a5ddfded.png" style="max-width: 100%;" _mstalt="449475" _msthash="281"></a></p>
<p dir="auto" _msttexthash="1526588843" _msthash="282">或者，您可以使用 Spring Boot Maven 插件直接从 Maven 运行它。如果你这样做，它会立即获取你在项目中所做的更改（对 Java 源文件的更改也需要编译 - 大多数人使用 IDE 来执行此操作）：</p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>./mvnw spring-boot:run</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="./mvnw spring-boot:run" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<blockquote>
<p dir="auto"><font _mstmutation="1" _msttexthash="301973997" _msthash="283">注意：如果您更喜欢使用 Gradle，则可以使用 构建应用程序，并在 中查找 jar 文件。</font><code>./gradlew build</code><code>build/libs</code></p>
</blockquote>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="10563033" _msthash="284">构建容器</h2><a id="user-content-building-a-container" class="anchor" aria-label="永久链接：构建容器" href="#building-a-container" _mstaria-label="761566" _msthash="285"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font _mstmutation="1" _msttexthash="416175682" _msthash="286">本项目中没有。您可以使用 Spring Boot 构建插件构建容器镜像（如果您有 docker 守护进程）：</font><code>Dockerfile</code></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>./mvnw spring-boot:build-image</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="./mvnw spring-boot:build-image" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="119113020" _msthash="287">如果您发现 Spring Petclinic 的错误/建议的改进</h2><a id="user-content-in-case-you-find-a-bugsuggested-improvement-for-spring-petclinic" class="anchor" aria-label="永久链接：如果您发现 Spring Petclinic 的错误/建议的改进" href="#in-case-you-find-a-bugsuggested-improvement-for-spring-petclinic" _mstaria-label="3555981" _msthash="288"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="72638761" _msthash="289">我们的问题跟踪器可<a href="https://github.com/spring-projects/spring-petclinic/issues" _istranslated="1">在此处</a>获得。</p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="17343547" _msthash="290">数据库配置</h2><a id="user-content-database-configuration" class="anchor" aria-label="永久链接：数据库配置" href="#database-configuration" _mstaria-label="923975" _msthash="291"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font _mstmutation="1" _msttexthash="1047697898" _msthash="292">在其默认配置中，Petclinic 使用内存数据库 （H2），该数据库
在启动时填充数据。h2 控制台在 、 中公开
并且可以使用 URL 检查数据库的内容。UUID 在启动时打印到控制台。</font><code>http://localhost:8080/h2-console</code><code>jdbc:h2:mem:&lt;uuid&gt;</code></p>
<p dir="auto"><font _mstmutation="1" _msttexthash="2371933109" _msthash="293">如果需要持久性数据库配置，则为 MySQL 和 PostgreSQL 提供了类似的设置。请注意，每当数据库类型发生变化时，应用程序都需要使用不同的配置文件运行：对于 MySQL 或 PostgreSQL。有关如何设置活动配置文件的更多详细信息，请参阅 <a href="https://docs.spring.io/spring-boot/how-to/properties-and-configuration.html#howto.properties-and-configuration.set-active-spring-profiles" rel="nofollow" _mstmutation="1" _istranslated="1">Spring Boot 文档</a>。</font><code>spring.profiles.active=mysql</code><code>spring.profiles.active=postgres</code></p>
<p dir="auto" _msttexthash="280311005" _msthash="294">您可以使用适用于您的操作系统的任何安装程序在本地启动 MySQL 或 PostgreSQL 或使用 docker：</p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>docker run -e MYSQL_USER=petclinic -e MYSQL_PASSWORD=petclinic -e MYSQL_ROOT_PASSWORD=root -e MYSQL_DATABASE=petclinic -p 3306:3306 mysql:9.1</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="docker run -e MYSQL_USER=petclinic -e MYSQL_PASSWORD=petclinic -e MYSQL_ROOT_PASSWORD=root -e MYSQL_DATABASE=petclinic -p 3306:3306 mysql:9.1" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto" _msttexthash="2285010" _msthash="295">或</p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>docker run -e POSTGRES_USER=petclinic -e POSTGRES_PASSWORD=petclinic -e POSTGRES_DB=petclinic -p 5432:5432 postgres:17.0</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="docker run -e POSTGRES_USER=petclinic -e POSTGRES_PASSWORD=petclinic -e POSTGRES_DB=petclinic -p 5432:5432 postgres:17.0" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto" _msttexthash="75092992" _msthash="296">提供了有关 <a href="https://github.com/spring-projects/spring-petclinic/blob/main/src/main/resources/db/mysql/petclinic_db_setup_mysql.txt" _istranslated="1">MySQL</a> 和 <a href="https://github.com/spring-projects/spring-petclinic/blob/main/src/main/resources/db/postgres/petclinic_db_setup_postgres.txt" _istranslated="1">PostgreSQL</a> 的更多文档。</p>
<p dir="auto"><font _mstmutation="1" _msttexthash="502685690" _msthash="297">除了 vanilla，您还可以使用提供的文件来启动数据库容器。每个 API 都有一个以 Spring 配置文件命名的服务：</font><code>docker</code><code>docker-compose.yml</code></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>docker compose up mysql</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="docker compose up mysql" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto" _msttexthash="2285010" _msthash="298">或</p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>docker compose up postgres</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="docker compose up postgres" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="21244782" _msthash="299">测试应用程序</h2><a id="user-content-test-applications" class="anchor" aria-label="永久链接： 测试应用程序" href="#test-applications" _mstaria-label="683332" _msthash="300"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font _mstmutation="1" _msttexthash="3943180813" _msthash="301">在开发时，我们建议您使用在 （使用默认 H2 数据库并添加 Spring Boot Devtools） 和 中设置为方法的测试应用程序。这些设置是为了让您可以在 IDE 中运行应用程序以获得快速反馈，还可以针对相应的数据库运行与集成测试相同的类。MySql 集成测试使用 Testcontainers 在 Docker 容器中启动数据库，而 Postgres 测试使用 Docker Compose 执行相同的操作。</font><code>main()</code><code>PetClinicIntegrationTests</code><code>MySqlTestApplication</code><code>PostgresIntegrationTests</code></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="6713564" _msthash="302">编译 CSS</h2><a id="user-content-compiling-the-css" class="anchor" aria-label="永久链接：编译 CSS" href="#compiling-the-css" _mstaria-label="605826" _msthash="303"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font _mstmutation="1" _msttexthash="1369291794" _msthash="304">在 中有一个 。它是从源生成的，并与 <a href="https://getbootstrap.com/" rel="nofollow" _mstmutation="1" _istranslated="1">Bootstrap</a> 库相结合。如果对 进行更改或升级 Bootstrap，则需要使用 Maven 配置文件 “css” 重新编译 CSS 资源，即 .Gradle 没有用于编译 CSS 的构建配置文件。</font><code>petclinic.css</code><code>src/main/resources/static/resources/css</code><code>petclinic.scss</code><code>scss</code><code>./mvnw package -P css</code></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="13377221" _msthash="305">在 IDE 中使用 Petclinic</h2><a id="user-content-working-with-petclinic-in-your-ide" class="anchor" aria-label="永久链接：在 IDE 中使用 Petclinic" href="#working-with-petclinic-in-your-ide" _mstaria-label="1339390" _msthash="306"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto" _msttexthash="9792913" _msthash="307">先决条件</h3><a id="user-content-prerequisites" class="anchor" aria-label="永久链接：先决条件" href="#prerequisites" _mstaria-label="566982" _msthash="308"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="70319509" _msthash="309">您的系统中应安装以下项目：</p>
<ul dir="auto">
<li _msttexthash="128469341" _msthash="310">Java 17 或更高版本（完整的 JDK，不是 JRE）</li>
<li><a href="https://help.github.com/articles/set-up-git" _msttexthash="19031766" _msthash="311">Git 命令行工具</a></li>
<li><font _mstmutation="1" _msttexthash="14833468" _msthash="312">您的首选 IDE</font><ul dir="auto">
<li><font _mstmutation="1" _msttexthash="716544699" _msthash="313">使用 m2e 插件的 Eclipse。注意：当 m2e 可用时，对话框中有一个 m2 图标。如果 m2e 为
不存在，请按照<a href="https://www.eclipse.org/m2e/" rel="nofollow" _mstmutation="1" _istranslated="1">此处的</a>安装过程进行操作</font><code>Help -&gt; About</code></li>
<li _msttexthash="48914502" _msthash="314"><a href="https://spring.io/tools" rel="nofollow" _istranslated="1">Spring 工具套件</a> （STS）</li>
<li><a href="https://www.jetbrains.com/idea/" rel="nofollow" _msttexthash="11009700" _msthash="315">IntelliJ 理念</a></li>
<li><a href="https://code.visualstudio.com" rel="nofollow" _msttexthash="6373003" _msthash="316">VS 代码</a></li>
</ul>
</li>
</ul>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto" _msttexthash="6619015" _msthash="317">步骤</h3><a id="user-content-steps" class="anchor" aria-label="永久链接：步骤" href="#steps" _mstaria-label="277654" _msthash="318"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ol dir="auto">
<li>
<p dir="auto" _msttexthash="37561290" _msthash="319">在命令行上运行：</p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>git clone https://github.com/spring-projects/spring-petclinic.git</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="git clone https://github.com/spring-projects/spring-petclinic.git" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</li>
<li>
<p dir="auto" _msttexthash="29007966" _msthash="320">在 Eclipse 或 STS 中：</p>
<p dir="auto"><font _mstmutation="1" _msttexthash="130275951" _msthash="321">通过 打开项目，然后选择克隆存储库的根目录。</font><code>File -&gt; Import -&gt; Maven -&gt; Existing Maven project</code></p>
<p dir="auto"><font _mstmutation="1" _msttexthash="732880343" _msthash="322">然后在命令行上构建或使用 Eclipse 启动器（右键单击项目和 ）生成 CSS。通过右键单击应用程序并选择 来运行应用程序的 main 方法。</font><code>./mvnw generate-resources</code><code>Run As -&gt; Maven install</code><code>Run As -&gt; Java Application</code></p>
</li>
<li>
<p dir="auto" _msttexthash="32795269" _msthash="323">IntelliJ IDEA 内部：</p>
<p dir="auto"><font _mstmutation="1" _msttexthash="118860638" _msthash="324">在主菜单中，选择并选择 Petclinic <a href="/spring-projects/spring-petclinic/blob/main/pom.xml" _mstmutation="1" _istranslated="1">pom.xml</a>。点击按钮。</font><code>File -&gt; Open</code><code>Open</code></p>
<ul dir="auto">
<li>
<p dir="auto"><font _mstmutation="1" _msttexthash="461520527" _msthash="325">CSS 文件是从 Maven 内部版本生成的。您可以在命令行上构建它们，也可以右键单击项目，然后按 。</font><code>./mvnw generate-resources</code><code>spring-petclinic</code><code>Maven -&gt; Generates sources and Update Folders</code></p>
</li>
<li>
<p dir="auto"><font _mstmutation="1" _msttexthash="689639977" _msthash="326">如果您使用的是最新的 Ultimate 版本，则应为您创建一个名为 的运行配置。否则，请右键单击主类并选择 来运行应用程序。</font><code>PetClinicApplication</code><code>PetClinicApplication</code><code>Run 'PetClinicApplication'</code></p>
</li>
</ul>
</li>
<li>
<p dir="auto" _msttexthash="8239088" _msthash="327">导航到 Petclinic</p>
<p dir="auto" _msttexthash="33018440" _msthash="328">在浏览器中访问 <a href="http://localhost:8080" rel="nofollow" _istranslated="1">http://localhost:8080</a>。</p>
</li>
</ol>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="28730091" _msthash="329">寻找特别优惠？</h2><a id="user-content-looking-for-something-in-particular" class="anchor" aria-label="永久链接： 寻找特别的东西？" href="#looking-for-something-in-particular" _mstaria-label="1571271" _msthash="330"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<markdown-accessiblity-table data-catalyst=""><table>
<thead>
<tr>
<th _msttexthash="16009201" _msthash="331">Spring Boot 配置</th>
<th _msttexthash="23313472" _msthash="332">类或 Java 属性文件</th>
</tr>
</thead>
<tbody>
<tr>
<td _msttexthash="5136625" _msthash="333">主类</td>
<td><a href="https://github.com/spring-projects/spring-petclinic/blob/main/src/main/java/org/springframework/samples/petclinic/PetClinicApplication.java" _msttexthash="20778342" _msthash="334">宠物诊所应用</a></td>
</tr>
<tr>
<td _msttexthash="10380513" _msthash="335">属性文件</td>
<td><a href="https://github.com/spring-projects/spring-petclinic/blob/main/src/main/resources" _msttexthash="530127" _msthash="336">application.properties</a></td>
</tr>
<tr>
<td _msttexthash="5392257" _msthash="337">缓存</td>
<td><a href="https://github.com/spring-projects/spring-petclinic/blob/main/src/main/java/org/springframework/samples/petclinic/system/CacheConfiguration.java" _msttexthash="13985166" _msthash="338">缓存配置</a></td>
</tr>
</tbody>
</table></markdown-accessiblity-table>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="48970662" _msthash="339">有趣的 Spring Petclinic 分支和分叉</h2><a id="user-content-interesting-spring-petclinic-branches-and-forks" class="anchor" aria-label="永久链接：有趣的 Spring Petclinic 分支和分支" href="#interesting-spring-petclinic-branches-and-forks" _mstaria-label="2302235" _msthash="340"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="2008709742" _msthash="341"><a href="https://github.com/spring-projects/spring-petclinic" _istranslated="1">spring-projects</a> GitHub 组织中的 Spring Petclinic “main” 分支是基于 Spring Boot 和 Thymeleaf 的 “规范” 实现。GitHub 组织 <a href="https://github.com/spring-petclinic" _istranslated="1">spring-petclinic</a> 中有很多<a href="https://spring-petclinic.github.io/docs/forks.html" rel="nofollow" _istranslated="1">分支</a>。如果您有兴趣使用不同的技术堆栈来实现 Pet Clinic，请加入那里的社区。</p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="38423398" _msthash="342">与其他开源项目的交互</h2><a id="user-content-interaction-with-other-open-source-projects" class="anchor" aria-label="永久链接：与其他开源项目的交互" href="#interaction-with-other-open-source-projects" _mstaria-label="2095223" _msthash="343"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="2592653895" _msthash="344">在 Spring Petclinic 应用程序上工作最好的部分之一是，我们有机会直接与许多开源项目合作。我们发现了各种主题的 bug/建议的改进，比如 Spring、Spring Data、Bean Validation 甚至 Eclipse！在许多情况下，它们在短短几天内就被修复/实施。
以下是它们的列表：</p>
<markdown-accessiblity-table data-catalyst=""><table>
<thead>
<tr>
<th _msttexthash="4389879" _msthash="345">名字</th>
<th _msttexthash="7555418" _msthash="346">问题</th>
</tr>
</thead>
<tbody>
<tr>
<td _msttexthash="77617917" _msthash="347">Spring JDBC：简化NamedParameterJdbcTemplate的使用</td>
<td _msttexthash="4721873" _msthash="348"><a href="https://jira.springsource.org/browse/SPR-10256" rel="nofollow" _istranslated="1">SPR-10256</a> 和 <a href="https://jira.springsource.org/browse/SPR-10257" rel="nofollow" _istranslated="1">SPR-10257</a></td>
</tr>
<tr>
<td _msttexthash="217936303" _msthash="349">Bean Validation / Hibernate Validator：简化 Maven 依赖项和向后兼容性</td>
<td _msttexthash="3778463" _msthash="350"><a href="https://hibernate.atlassian.net/browse/HV-790" rel="nofollow" _istranslated="1">HV-790</a> 和 <a href="https://hibernate.atlassian.net/browse/HV-792" rel="nofollow" _istranslated="1">HV-792</a></td>
</tr>
<tr>
<td _msttexthash="147620512" _msthash="351">Spring Data：在使用 JPQL 查询时提供更大的灵活性</td>
<td><a href="https://jira.springsource.org/browse/DATAJPA-292" rel="nofollow" _msttexthash="5074251" _msthash="352">数据JPA-292</a></td>
</tr>
</tbody>
</table></markdown-accessiblity-table>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="6354283" _msthash="353">贡献</h2><a id="user-content-contributing" class="anchor" aria-label="永久链接： 贡献" href="#contributing" _mstaria-label="521066" _msthash="354"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="205844678" _msthash="355"><a href="https://github.com/spring-projects/spring-petclinic/issues" _istranslated="1">问题跟踪器</a>是 bug 报告、功能请求和提交拉取请求的首选渠道。</p>
<p dir="auto" _msttexthash="1636528608" _msthash="356">对于拉取请求，<a href="/spring-projects/spring-petclinic/blob/main/.editorconfig" _istranslated="1">编辑器配置</a>中提供了编辑器首选项，以便在常见的文本编辑器中轻松使用。在 <a href="https://editorconfig.org" rel="nofollow" _istranslated="1">https://editorconfig.org</a> 阅读更多内容并下载插件。如果您之前没有这样做过，请填写并提交<a href="https://cla.pivotal.io/sign/spring" rel="nofollow" _istranslated="1">贡献者许可协议</a>。</p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto" _msttexthash="9675445" _msthash="357">许可证</h2><a id="user-content-license" class="anchor" aria-label="永久链接：许可证" href="#license" _mstaria-label="331903" _msthash="358"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto" _msttexthash="195179842" _msthash="359">Spring PetClinic 示例应用程序在 <a href="https://www.apache.org/licenses/LICENSE-2.0" rel="nofollow" _istranslated="1">Apache 许可证</a>的 2.0 版本下发布。</p>
</article></div>
