---

layout: col-sidebar
title: OWASP Dependency-Track
site_side: true
tags: dependency-track dtrack sca scrm sbom bom component-analysis supply-chain cpe purl license vulnerability impact
level: 0
type: tool
pitch: Intelligent Supply Chain Component Analysis platform that allows organizations to identify and reduce risk from the use of third-party and open source components.

auto-migrated: 1
---

This is an example of a Project or Chapter Page.
# Main

<div style="width:100%;height:90px;border:0,margin:0;overflow: hidden;">

![_flagship_big.jpg](_flagship_big.jpg "_flagship_big.jpg")

</div>

<table>
<tbody>
<tr class="odd">
<td><h2 id="owasp_dependency_track">OWASP Dependency-Track</h2>
<p>Modern applications leverage the availability of existing components for use as building blocks in application development. By using existing components, organizations can dramatically decrease time-to-market. Reusing existing components however, comes at a cost. Organizations that build on top of existing components assume risk for software they did not create. Vulnerabilities in third-party components are inherited by all applications that use those components. The <a href="OWASP_Top_Ten" title="wikilink">OWASP Top Ten</a> (2013 and 2017) both recognize the risk of <a href="Top_10_2013-A9-Using_Components_with_Known_Vulnerabilities" title="wikilink">using components with known vulnerabilities</a>.</p>
<p>Modern applications leverage the availability of existing components for use as building blocks in application development. By using existing components, organizations can dramatically decrease time-to-market. Reusing existing components however, comes at a cost. Organizations that build on top of existing components assume risk for software they did not create. Vulnerabilities in third-party components are inherited by all applications that use those components. The <a href="OWASP_Top_Ten" title="wikilink">OWASP Top Ten</a> (2013 and 2017) both recognize the risk of <a href="Top_10_2013-A9-Using_Components_with_Known_Vulnerabilities" title="wikilink">using components with known vulnerabilities</a>.</p>
<p>Dependency-Track is a Software Composition Analysis (SCA) platform that keeps track of all third-party components used in all the applications an organization creates or consumes. It integrates with multiple vulnerability databases including the <a href="https://nvd.nist.gov/">National Vulnerability Database</a> (NVD), <a href="https://www.npmjs.com/advisories">NPM Public Advisories</a>, <a href="https://ossindex.sonatype.org/">Sonatype OSS Index</a>, and <a href="https://vulndb.cyberriskanalytics.com">VulnDB</a> from <a href="https://www.riskbasedsecurity.com">Risk Based Security</a>. Dependency-Track monitors all applications in its portfolio in order to proactively identify vulnerabilities in components that are placing your applications at risk. Use of Dependency-Track can play a vital role in an overall <a href="https://csrc.nist.gov/Projects/Supply-Chain-Risk-Management">Cyber Supply Chain Risk Management</a> (C-SCRM) program by fulfilling many of the recommendations laid out by <a href="https://www.safecode.org/wp-content/uploads/2017/05/SAFECode_TPC_Whitepaper.pdf">SAFECode</a>.</p>
<p>Dependency-Track is a Software Composition Analysis (SCA) platform that keeps track of all third-party components used in all the applications an organization creates or consumes. It integrates with multiple vulnerability databases including the <a href="https://nvd.nist.gov/">National Vulnerability Database</a> (NVD), <a href="https://www.npmjs.com/advisories">NPM Public Advisories</a>, <a href="https://ossindex.sonatype.org/">Sonatype OSS Index</a>, and <a href="https://vulndb.cyberriskanalytics.com">VulnDB</a> from <a href="https://www.riskbasedsecurity.com">Risk Based Security</a>. Dependency-Track monitors all applications in its portfolio in order to proactively identify vulnerabilities in components that are placing your applications at risk. Use of Dependency-Track can play a vital role in an overall <a href="https://csrc.nist.gov/Projects/Supply-Chain-Risk-Management">Cyber Supply Chain Risk Management</a> (C-SCRM) program by fulfilling many of the recommendations laid out by <a href="https://www.safecode.org/wp-content/uploads/2017/05/SAFECode_TPC_Whitepaper.pdf">SAFECode</a>.</p>
<p>Dependency-Track is designed to be used in an automated DevOps environment where BoM (bill-of-material) formats are automatically ingested during CI/CD. Use of the <a href="https://plugins.jenkins.io/dependency-track">Dependency-Track Jenkins Plugin</a> is highly recommended for this purpose and is well suited for use in Jenkins Pipeline. In such an environment, Dependency-Track enables your DevOps teams to accelerate while still keeping tabs on component usage and any inherited risk.</p>
<p>Dependency-Track is designed to be used in an automated DevOps environment where BoM (bill-of-material) formats are automatically ingested during CI/CD. Use of the <a href="https://plugins.jenkins.io/dependency-track">Dependency-Track Jenkins Plugin</a> is highly recommended for this purpose and is well suited for use in Jenkins Pipeline. In such an environment, Dependency-Track enables your DevOps teams to accelerate while still keeping tabs on component usage and any inherited risk.</p>
<p>Dependency-Track can also be used to monitor vulnerabilities in COTS (commercial off-the-shelf) software.</p>
<p>Dependency-Track can also be used to monitor vulnerabilities in COTS (commercial off-the-shelf) software.</p>
<figure>
<figure>
<img src="Integrations.png" title="Integrations.png" alt="Integrations.png" /><figcaption>Integrations.png</figcaption>
<img src="Integrations.png" title="Integrations.png" alt="Integrations.png" /><figcaption>Integrations.png</figcaption>
</figure>
</figure>
<h2 id="features">Features</h2>
<h2 id="features">Features</h2>
<ul>
<ul>
<li>Increases visibility into the use of vulnerable and outdated components</li>
<li>Increases visibility into the use of vulnerable and outdated components</li>
<li>Flexible data model supporting an unlimited number of projects and components</li>
<li>Flexible data model supporting an unlimited number of projects and components</li>
<li>Tracks vulnerabilities and inherited risk
<li>Tracks vulnerabilities and inherited risk
<ul>
<ul>
<li>by component</li>
<li>by component</li>
<li>by project</li>
<li>by project</li>
<li>across entire portfolio</li>
<li>across entire portfolio</li>
</ul></li>
</ul></li>
<li>Tracks usage of out-of-date components</li>
<li>Tracks usage of out-of-date components</li>
<li>Includes a comprehensive auditing workflow for triaging results</li>
<li>Includes a comprehensive auditing workflow for triaging results</li>
<li>Configurable notifications supporting Slack, Microsoft Teams, Webhooks, and Email</li>
<li>Configurable notifications supporting Slack, Microsoft Teams, Webhooks, and Email</li>
<li>Supports standardized SPDX license ID’s and tracks license use by component</li>
<li>Supports standardized SPDX license ID’s and tracks license use by component</li>
<li>Supports <a href="http://cyclonedx.org">CycloneDX</a> and <a href="https://spdx.org/">SPDX</a> bill-of-material formats and Dependency-Check XML</li>
<li>Supports <a href="http://cyclonedx.org">CycloneDX</a> and <a href="https://spdx.org/">SPDX</a> bill-of-material formats and Dependency-Check XML</li>
<li>Easy to read metrics for components, projects, and portfolio</li>
<li>Easy to read metrics for components, projects, and portfolio</li>
<li>Provides a reliable mirror of the NVD data feed</li>
<li>Provides a reliable mirror of the NVD data feed</li>
<li>API-first design facilitates easy integration with other systems</li>
<li>API-first design facilitates easy integration with other systems</li>
<li>API documentation available in Swagger 2.0 (OpenAPI 3 support coming soon)</li>
<li>API documentation available in Swagger 2.0 (OpenAPI 3 support coming soon)</li>
<li>Supports internally managed users, Active Directory/LDAP, and API Keys</li>
<li>Supports internally managed users, Active Directory/LDAP, and API Keys</li>
<li>Simple to install and configure. Get up and running in just a few minutes</li>
<li>Simple to install and configure. Get up and running in just a few minutes</li>
</ul>
</ul>
<h2 id="distributions">Distributions</h2>
<h2 id="distributions">Distributions</h2>
<p>Dependency-Track supports the following three deployment options:</p>
<p>Dependency-Track supports the following three deployment options:</p>
<ul>
<ul>
<li>Executable WAR</li>
<li>Executable WAR</li>
<li>Conventional WAR</li>
<li>Conventional WAR</li>
<li>Docker container</li>
<li>Docker container</li>
</ul>
</ul>
<h2 id="licensing">Licensing</h2>
<h2 id="licensing">Licensing</h2>
<p>OWASP Dependency-Track is licensed under the <a href="https://www.apache.org/licenses/LICENSE-2.0">Apache 2.0 license</a>.</p></td>
<p>OWASP Dependency-Track is licensed under the <a href="https://www.apache.org/licenses/LICENSE-2.0">Apache 2.0 license</a>.</p></td>
<img src="Dependency-Track-logo-300x100.png" title="Dependency-Track-logo-300x100.png" alt="Dependency-Track-logo-300x100.png" width="250" /><figcaption>Dependency-Track-logo-300x100.png</figcaption>
</figure>
<h2 id="quick_download">Quick Download</h2>
<p>Ready-to-deploy distributions are available from the Dependency-Track website</p>
<ul>
<li><a href="https://dependencytrack.org/">Website</a></li>
<li><a href="https://github.com/DependencyTrack">Source Code</a></li>
</ul>
<h2 id="news_and_events">News and Events</h2>
<ul>
<li>[22 Dec 2018] v3.4.0 Released</li>
<li>[13 Nov 2018] v3.3.1 Released</li>
<li>[25 Oct 2018] v3.3.0 Released</li>
<li>[02 Oct 2018] v3.2.2 Released</li>
<li>[21 Sep 2018] v3.2.1 Released</li>
<li>[06 Sep 2018] v3.2.0 Released</li>
<li>[19 Jun 2018] v3.1.0 Released</li>
<li>[02 May 2018] v3.0.4 Released</li>
<li>[13 Apr 2018] v3.0.3 Released</li>
<li>[30 Mar 2018] v3.0.2 Released</li>
<li>[27 Mar 2018] v3.0.1 Released</li>
<li>[26 Mar 2018] v3.0.0 Released</li>
<li>[08 Oct 2017] v3.0 <a href="https://groups.google.com/forum/#!topic/dependency-track/0PUJI5rNgzI">Updates to community</a></li>
<li>[16 Jun 2017] <a href="https://www.youtube.com/watch?v=88YAlzuDH04&amp;t=50s">Presentation at OWASP Summit 2017</a></li>
<li>[10 Dec 2016] Work begins on v3.0</li>
</ul>
<h2 id="media">Media</h2>
<p><a href="https://www.youtube.com/channel/UC8xdttysl3gNAQYvk1J9Efg">OWASP Dependency-Track Channel (YouTube)</a></p>
<p><a href="https://www.appsecpodcast.org/2018/04/12/dependency-check-and-dependency-track-s03e13/">AppSec Podcast (S03E13)</a></p>
<h2 id="documentation">Documentation</h2>
<p><a href="https://docs.dependencytrack.org">Dependency-Track Documentation</a></p>
<h2 id="project_leader">Project Leader</h2>
<p><a href="User:Steve_Springett" title="wikilink">Steve Springett</a></p>
<h2 id="related_projects">Related Projects</h2>
<ul>
<li><a href="OWASP_Dependency_Check" title="wikilink">OWASP Dependency-Check</a></li>
</ul>
<h2 id="classifications">Classifications</h2>
<table>
<tbody>
<tr class="odd">
<img src="Mature_projects.png" title="Mature_projects.png" alt="Mature_projects.png" width="100" /><figcaption>Mature_projects.png</figcaption>
</figure></td>
</tr>
<tr class="even">
<img src="Project_Type_Files_TOOL.jpg" title="Project_Type_Files_TOOL.jpg" alt="Project_Type_Files_TOOL.jpg" /><figcaption>Project_Type_Files_TOOL.jpg</figcaption>
</figure></td>
</tr>
</tbody>
</table></td>
</tr>
</tbody>
</table>

# Screenshots

[File:Dependency-Track_Screenshot-_Dashboard.png|Dashboard](File:Dependency-Track_Screenshot-_Dashboard.png%7CDashboard)
[File:Dependency-Track_Screenshot_-_Projects.png|Projects](File:Dependency-Track_Screenshot_-_Projects.png%7CProjects)
[File:Dependency-Track_Screenshot_-_Vulnerable_Component.png|Vulnerable](File:Dependency-Track_Screenshot_-_Vulnerable_Component.png%7CVulnerable)
Component
[File:Dependency-Track_Screenshot_-_Vulnerability.png|Vulnerability](File:Dependency-Track_Screenshot_-_Vulnerability.png%7CVulnerability)

# Acknowledgements

This project would not be possible without the existence of the
[OWASP_Dependency_Check](OWASP_Dependency_Check "wikilink") project.
Special thanks to Jeremy Long and the Dependency-Check core team for
their hard work.

## Dependency-Track Core Team

  - [Steve Springett](User:Steve_Springett "wikilink")

## Sponsors

Dependency-Track is created by a worldwide group of volunteers who have
dedicated their time, talent, or provided financial support to the
project.

The project would like to acknowledge and thank the following
organizations that have helped move this project forward

  - [Risk Based Security](https://www.riskbasedsecurity.com/)

OWASP Dependency-Track is an open source project, created by people who
believe that the knowledge of using vulnerable components should be
accessible to anyone with a desire to know. By supporting this project,
you'll allow the team to outsource testing, infrastructure, further
research and development efforts, and engage in outreach to various
communities that would benefit from this technology.

{{\#widget:PayPal Donation |target=_blank |budget=OWASP
Dependency-Track }}

# Road Map

Dependency-Track uses [GitHub
milestones](https://github.com/DependencyTrack/dependency-track/milestones)
to track roadmaps and future releases.

# Community

Feedback from the community is always encouraged. Tell us what you like,
what needs to be improved, and what features would be beneficial to your
organization.

Three ways to get involved:

  - [GitHub
    Issues](https://github.com/DependencyTrack/dependency-track/issues)
    - Collaborate on open issues
  - [Gitter](https://gitter.im/dependency-track/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
    - Chatroom built around GitHub
  - [Slack](https://owasp.slack.com/messages/proj-dependency-track) -
    The Dependency-Track Slack channel

Pull requests are highly encouraged. No contribution is too small. Do
you know how to create test cases? Help us out. Want to write (or
correct) some docs? Yes please... All contributions are appreciated.

# Project About

__NOTOC__ <headertabs />

[Category:OWASP Project](Category:OWASP_Project "wikilink")
[Category:OWASP_Builders](Category:OWASP_Builders "wikilink")
[Category:OWASP_Defenders](Category:OWASP_Defenders "wikilink")
[Category:OWASP Tool](Category:OWASP_Tool "wikilink") [Category:Flagship
Projects](Category:Flagship_Projects "wikilink")
