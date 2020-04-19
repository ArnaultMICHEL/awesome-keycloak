# Awesome Keycloak [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

# [<img src="https://www.keycloak.org/resources/images/keycloak_logo_480x108.png">](https://github.com/thomasdarimont/awesome-keycloak)

> Carefully curated list of awesome Keycloak resources.

A curated list of resources for learning about the Open Source Identity and Access Management solution Keycloak. 
Contains books, websites, blog posts, links to github Repositories.  

# Contributing
Contributions welcome. Add links through pull requests or create an issue to start a discussion.
[Please refer to the contributing guide for details](CONTRIBUTING.md).

# Contents

* [General](#general)
  * [Documentation](#docs)
    * [Keycloak Website](http://www.keycloak.org)
    * [Current Documentation](http://www.keycloak.org/documentation.html)
    * [Archived Documentation](http://www.keycloak.org/documentation-archive.html)
  * [Mailing Lists](#mailing-lists)
    * [User Mailing List](#user-mailing-list)
    * [Developer Mailing List](#dev-mailing-list)
    * [Mailing List Search](#mailing-list-search)
* [Articles](#articles)
* [Talks](#talks)
* [Presentations](#presentations)
* [Community Extensions](#community-extensions)
* [Integrations](#integrations)
* [Themes](#themes)
* [Docker](#docker)
* [Example Projects](#example-projects)
* [Benchmarks](#benchmarks)
* [Help](#help)
* [Commercial Offerings](#commercial-offerings)
* [Miscellaneous](#miscellaneous)

# General

## Documentation

*  [Keycloak Website](http://www.keycloak.org/)
*  [Current Documentation](http://www.keycloak.org/documentation.html)
*  [Archived Documentation](http://www.keycloak.org/documentation-archive.html)
*  [Product Documentation for Red Hat Single Sign-On](https://access.redhat.com/documentation/en/red-hat-single-sign-on/)

## Discussion Groups and Mailing Lists
*  [Keycloak Users Google Group](https://groups.google.com/forum/#!forum/keycloak-user)
*  [Keycloak Developers Google Group](https://groups.google.com/forum/#!forum/keycloak-dev)
*  [Keycloak Discourse Group](https://keycloak.discourse.group/)
*  [Keycloak Developer Chat](https://keycloak.zulipchat.com)
*  [Inactive - User Mailing List](https://lists.jboss.org/mailman/listinfo/keycloak-user)
*  [Inactive - Developer Mailing List](https://lists.jboss.org/mailman/listinfo/keycloak-dev)
*  [Mailing List Search](http://www.keycloak.org/search)
*  [Keycloak Subreddit](https://www.reddit.com/r/keycloak)

## Articles
*  [How to get Keycloak working with Docker](https://www.ivonet.nl/2015/05/23/Keycloak-Docker/)
*  [Single-Sign-On for Microservices and/or Java EE applications with Keycloak SSO](http://www.n-k.de/2016/06/keycloak-sso-for-microservices.html)
*  [Keycloak Admin Client(s) - multiple ways to manage your SSO system](http://www.n-k.de/2016/08/keycloak-admin-client.html)
*  [How to get the AccessToken of Keycloak in Spring Boot and/or Java EE](http://www.n-k.de/2016/05/how-to-get-accesstoken-from-keycloak-springboot-javaee.html)
*  [JWT authentication with Vert.x, Keycloak and Angular 2](http://paulbakker.io/java/jwt-keycloak-angular2/)
*  [Authenticating via Kerberos with Keycloak and Windows 2008 Active Directory](http://matthewcasperson.blogspot.de/2015/07/authenticating-via-kerberos-with.html)
*  [Deploying Keycloak with Ansible](https://adam.younglogic.com/2016/01/deploying-keycloak-via-ansible/)
*  [Easily secure your Spring Boot applications with Keycloak](https://developers.redhat.com/blog/2017/05/25/easily-secure-your-spring-boot-applications-with-keycloak/)
*  [How Red Hat re-designed its Single Sign On (SSO) architecture, and why](https://developers.redhat.com/blog/2016/10/04/how-red-hat-re-designed-its-single-sign-on-sso-architecture-and-why/)
*  [OAuth2, JWT, Open-ID Connect and other confusing things](http://giallone.blogspot.de/2017/06/oath2.html)
*  [X509 Authentication with Keycloak and JBoss Fuse](https://sjhiggs.github.io/fuse/sso/x509/smartcard/2017/03/29/fuse-hawtio-keycloak.html)
*  [Running Keycloak on OpenShift 3](https://medium.com/@sbose78/running-keycloak-on-openshift-3-8d195c0daaf6)
*  [Introducing Keycloak for Identity and Access Management](https://www.thomasvitale.com/introducing-keycloak-identity-access-management/)
*  [Keycloak Basic Configuration for Authentication and Authorisation](https://www.thomasvitale.com/keycloak-configuration-authentication-authorisation/)
*  [Keycloak on OpenShift Origin](https://medium.com/@james_devcomb/keycloak-on-openshift-origin-ee81d01dac97)
*  [Identity Management, One-Time-Passwords and Two-Factor-Auth with Spring Boot and Keycloak](http://www.hascode.com/2017/11/identity-management-one-time-passwords-and-two-factor-auth-with-spring-boot-and-keycloak/)
*  [Keycloak Identity Brokering with Openshift](https://developers.redhat.com/blog/2017/12/06/keycloak-identity-brokering-openshift/)
*  [OpenID Connect Identity Brokering with Red Hat Single Sign-On](https://developers.redhat.com/blog/2017/10/18/openid-connect-identity-brokering-red-hat-single-sign/)
*  [Authentication & user management is hard](https://eclipsesource.com/blogs/2018/01/11/authenticating-reverse-proxy-with-keycloak/)
*  [Securing Nginx with Keycloak](https://edhull.co.uk/blog/2018-06-06/keycloak-nginx)
*  [Secure kibana dashboards using keycloak](https://aboullaite.me/secure-kibana-keycloak/)
*  [Configuring NGINX for OAuth/OpenID Connect SSO with Keycloak/Red Hat SSO](https://developers.redhat.com/blog/2018/10/08/configuring-nginx-keycloak-oauth-oidc/)
*  [Keycloak Clustering Setup and Configuration Examples](https://github.com/fit2anything/keycloak-cluster-setup-and-configuration)
*  [MicroProfile JWT with Keycloak](https://kodnito.com/posts/microprofile-jwt-with-keycloak/)
*  [Keycloak Essentials](https://medium.com/keycloak/keycloak-essentials-86254b2f1872)
*  [SSO-session failover with Keycloak and AWS S3](https://medium.com/@georgijsr/sso-session-failover-with-keycloak-and-aws-s3-e0b1db985e12)
*  [KTOR and Keycloak: authentication with OpenId](https://medium.com/slickteam/ktor-and-keycloak-authentication-with-openid-ecd415d7a62e)
* [Keycloak: Core concepts of open source identity and access management](https://developers.redhat.com/blog/2019/12/11/keycloak-core-concepts-of-open-source-identity-and-access-management)
* [Who am I? Keycloak Impersonation API](https://blog.softwaremill.com/who-am-i-keycloak-impersonation-api-bfe7acaf051a)
* [Setup Keycloak Server on Ubuntu 18.04](https://medium.com/@hasnat.saeed/setup-keycloak-server-on-ubuntu-18-04-ed8c7c79a2d9)
* [Getting started with Keycloak](https://robferguson.org/blog/2019/12/24/getting-started-with-keycloak/)
* [Angular, OpenID Connect and Keycloak](https://robferguson.org/blog/2019/12/29/angular-openid-connect-keycloak/)
* [Angular, OAuth 2.0 Scopes and Keycloak](https://robferguson.org/blog/2019/12/31/angular-oauth2-keycloak/)
* [Keycloak, Flowable and OpenLDAP](https://robferguson.org/blog/2020/01/03/keycloak-flowable-and-openldap/)
* [How to exchange token from an external provider to a keycloak token](https://www.mathieupassenaud.fr/token-exchange-keycloak/)
* [Building an Event Listener SPI (Plugin) for Keycloak](https://dev.to/adwaitthattey/building-an-event-listener-spi-plugin-for-keycloak-2044)
* [Keycloak user migration – connect your legacy authentication system to Keycloak](https://codesoapbox.dev/keycloak-user-migration/)

## Talks
*  [JDD2015 - Keycloak Open Source Identity and Access Management Solution](https://www.youtube.com/watch?v=TuEkj25lbd0)
*  [2015 Using Tomcat and Keycloak in an iFrame](https://www.youtube.com/watch?v=nF_lw7uIxao)
*  [2016 You've Got Microservices Now Secure Them](https://www.youtube.com/watch?v=SfVhqf-rMQY)
*  [2016 Keycloak: Open Source Single Sign On - Sebastian Rose - AOE conf (german)](https://www.youtube.com/watch?v=wbKw0Bwyne4)
*  [2016 Sécuriser ses applications back et front facilement avec Keycloak (french)](https://www.youtube.com/watch?v=bVidgluUcg0)
*  [2016 Keycloak and Red Hat Mobile Application Platform](https://www.youtube.com/watch?v=4NBgiHM5aOA)
*  [2016 Easily secure your Front and back applications with KeyCloak](https://www.youtube.com/watch?v=RGp4HUKikts)
*  [2017 Easily secure your Spring Boot applications with Keycloak - Part 1](https://developers.redhat.com/video/youtube/vpgRTPFDHAw/)
*  [2017 Easily secure your Spring Boot applications with Keycloak - Part 2](https://developers.redhat.com/video/youtube/O5ePCWON08Y/)
*  [2018 How to secure your Spring Apps with Keycloak by Thomas Darimont @ Spring I/O 2018](https://www.youtube.com/watch?v=haHFoeWUj0w)
*  [2018 DevNation Live | A Deep Dive into Keycloak](https://www.youtube.com/watch?v=ZxpY_zZ52kU)
*  [2018 IDM Europe: WSO2 Identity Server vs. Keycloak (Dmitry Kann)](https://www.youtube.com/watch?v=hnjBiGsEDoU)
*  [2018 JPrime|Building an effective identity and access management architecture with Keycloak (Sebastien Blanc)](https://www.youtube.com/watch?v=bMqcGkCvUVQ)
*  [2018 WJAX| Sichere Spring-Anwendungen mit Keycloak](https://www.youtube.com/watch?v=6Z490EMcafs)
*  [2019 Spring I/O | Secure your Spring Apps with Keycloak](https://www.youtube.com/watch?v=KrOd5wIkqls)
*  [2019 DevoxxFR | Maitriser sa gestion de l'identité avec Keycloak (L. Benoit, T. Recloux, S. Blanc)](https://www.youtube.com/watch?v=0cziL__0-K8)

## Presentations
*  [Keycloak 101](https://stevenolen.github.io/kc101-talk/#1)

## Clients
*  [Official Keycloak Node.js Admin Client](https://github.com/keycloak/keycloak-admin-client/) ("Extremely Experimental")
*  [Keycloak Node.js TypeScript Admin Client by Canner](https://github.com/Canner/keycloak-admin/)
*  [Keycloak Go Client by Cloudtrust](https://github.com/cloudtrust/keycloak-client)

## Community Extensions
*  [Keycloak Extensions List](https://www.keycloak.org/extensions.html)
*  [Keycloak: Link IdP Login with User Provider](https://github.com/ohioit/keycloak-link-idp-with-user)
*  [Client Owner Manager: Control who can edit a client](https://github.com/cyclone-project/cyclone-client-registration)
*  [Keyloak Proxy written in Go](https://github.com/gambol99/keycloak-proxy)
*  [Script based ProtocolMapper extension for SAML](https://github.com/cloudtrust/keycloak-client-mappers)
*  [Realm export REST resource by Cloudtrust](https://github.com/cloudtrust/keycloak-export)
*  [Keycloak JDBC Ping Setup by moremagic](https://github.com/moremagic/keycloak-jdbc-ping)
*  [SMS 2 Factor Authentication for Keycloak via AWS SNS](https://github.com/nickpack/keycloak-sms-authenticator-sns)
*  [SMS 2 Factor Authentiation for Keycloak via SMS by Alliander](https://github.com/Alliander/keycloak-sms-authenticator)
*  [Identity Provider for vk.com](https://github.com/mrk08/keycloak-vk)
*  [CAS Protocol Support](https://github.com/Doccrazy/keycloak-protocol-cas)
*  [WS-FED Support](https://github.com/cloudtrust/keycloak-wsfed)
*  [Keycloak Discord Support](https://github.com/wadahiro/keycloak-discord)
*  [Keycloak Login with User Attribute](https://github.com/cnieg/keycloak-login-attribute)

## Integrations
*  [Official Keycloak Node.js Connect Adapter](https://github.com/keycloak/keycloak-nodejs-connect)
*  [Keycloak support for Aurelia](https://github.com/waynepennington/aurelia-keycloak)
*  [Keycloak OAuth2 Auth for PHP](https://github.com/stevenmaguire/oauth2-keycloak)
*  [Jenkins Keycloak Authentication Plugin](https://github.com/jenkinsci/keycloak-plugin)
*  [Meteor Keycloak Accounts](https://github.com/mxab/meteor-keycloak)
*  [HapiJS Keycloak Auth](https://github.com/felixheck/hapi-auth-keycloak)
*  [zmartzone mod_auth_openidc for Apache 2.x](https://github.com/zmartzone/mod_auth_openidc)
*  [Duo Security MFA Authentication for Keycloak](https://github.com/mulesoft-labs/keycloak-duo-spi)
*  [Extension Keycloak facilitant l'utilisation de FranceConnect](https://github.com/InseeFr/Keycloak-FranceConnect)
*  [Ambassador Keycloak Support](https://www.getambassador.io/reference/idp-support/keycloak/)
*  [Keycloak Python Client](https://github.com/akhilputhiry/keycloak-client)
*  [Keycloak Terraform Provider](https://github.com/mrparkers/terraform-provider-keycloak)
*  [Keycloak ADFS OpenID Connect](https://www.michaelboeynaems.com/keycloak-ADFS-OIDC.html)
*  [React/NextJS Keycloak Bindings](https://github.com/panz3r/react-keycloak)
*  [Keycloak Open-Shift integration](https://github.com/keycloak/openshift-integration)

## Quick demo Videos
* [Keycloak with istio envoy jwt-auth proxy](https://www.youtube.com/watch?v=wscX7JMfuBI)

## Themes
*  [Community Keycloak Ionic Theme](https://github.com/lfryc/keycloak-ionic-theme)
*  [A Keycloak theme based on the AdminLTE UI library](https://github.com/MAXIMUS-DeltaWare/adminlte-keycloak-theme)
*  [GOV.UK Theme](https://github.com/UKHomeOffice/keycloak-theme-govuk)
*  [Carbon Design](https://github.com/httpsOmkar/keycloak-carbon-theme)

## Docker
*  [Official Keycloak Docker Images](https://github.com/jboss-dockerfiles/keycloak)
*  [Keycloak Examples as Docker Image](https://hub.docker.com/r/jboss/keycloak-examples)
*  [Keycloak Maven SDK for managing the entire lifecycle of your extensions with Docker](https://github.com/OpenPj/keycloak-docker-quickstart)

## Kubernetes
*  [Deprecated Keycloak Helm Chart](https://github.com/codecentric/helm-charts/tree/master/charts/keycloak)
*  [codecentric Keycloak Helm Chart](https://github.com/codecentric/helm-charts/tree/master/charts/keycloak)
*  [Import / Export Keycloak Config](https://gist.github.com/unguiculus/19618ef57b1863145262191944565c9d)
*  [keycloak-operator](https://github.com/keycloak/keycloak-operator)

## Tools
*  [keycloakmigration: Manage your Keycloak configuration with code](https://github.com/klg71/keycloakmigration)

## Example Projects
*  [Official Examples](https://github.com/keycloak/keycloak/tree/master/examples)
*  [Keycloak Quickstarts](https://github.com/keycloak/keycloak-quickstarts)
*  [Drupal 7.0 with Keycloak](https://gist.github.com/thomasdarimont/17fa146c4fb5440d7fc2ee6322ec392d)
*  [Securing Realm Resources With Custom Roles](https://github.com/dteleguin/custom-admin-roles)
*  [BeerCloak: a comprehensive KeyCloak extension example](https://github.com/dteleguin/beercloak)
*  [KeyCloak Extensions: Securing Realm Resources With Custom Roles](https://github.com/dteleguin/custom-admin-roles)
*  [Red Hat Single Sign-On Labs](https://github.com/RedHatWorkshops/red-hat-sso)
*  [Spring Boot Keycloak Tutorial](https://github.com/sebastienblanc/spring-boot-keycloak-tutorial)
*  [Custom Keycloak Docker Image of Computer Science House of RIT](https://github.com/ComputerScienceHouse/keycloak-docker)
*  [Example of custom password hash SPI for Keycloak](https://github.com/pavelbogomolenko/keycloak-custom-password-hash)
*  [Example for a custom http-client-provider with Proxy support](https://github.com/xiaoyvr/custom-http-client-provider)
*  [Monitor your keycloak with prometheus](https://github.com/larscheid-schmitzhermes/keycloak-monitoring-prometheus)
*  [Custom User Storage Provider .ear with jboss-cli setup](https://github.com/thomasdarimont/keycloak-user-storage-provider-demo)
*  [Keycloak - Experimental extensions by Stian Thorgersen/Keycloak](https://github.com/stianst/keycloak-experimental)
*  [Securing Spring Boot Admin & Actuator Endpoints with Keycloak](https://github.com/thomasdarimont/spring-boot-admin-keycloak-example)
*  [A Keycloak Mobile Implementation using Angular v4 and Ionic v3](https://github.com/tomjackman/keyonic-v2)
*  [Example for Securing Apps with Keycloak on Kubernetes](https://github.com/stianst/demo-kubernetes)
*  [Example for Securing AspDotNet Core Apps with Keycloak](https://github.com/thomasdarimont/kc-dnc-demo)
*  [Example for passing custom URL parameters to a Keycloak theme for dynamic branding](https://github.com/dteleguin/keycloak-dynamic-branding)
*  [Angular Webapp secured with Keycloak](https://github.com/CodepediaOrg/bookmarks.dev)
*  [Keycloak Theme Development Kit](https://github.com/anthonny/kit-keycloak-theme)

## Benchmarks
*  [Gatling based Benchmark by @rvansa](https://github.com/rvansa/keycloak-benchmark)

## Help
* [Keycloak on Stackoverflow](https://stackoverflow.com/questions/tagged/keycloak)

## Commercial Offerings
*  [Red Hat Single Sign-On](https://access.redhat.com/products/red-hat-single-sign-on)
*  [INTEGSOFT UNIFIED USER CREDENTIALS WITH KEYCLOAK SSO](https://www.integsoft.cz/en/sso.html#what-is-sso)
*  [JIRA SSO Plugin by codecentric](https://marketplace.atlassian.com/plugins/de.codecentric.atlassian.oidc.jira-oidc-plugin/server/overview)

## Miscellaneous
*  [Find sites using Keycloak with google](https://www.google.de/search?q=inurl%3Aauth+inurl%3Arealms+inurl%3Aprotocol&oq=inurl%3A&client=ubuntu&sourceid=chrome&ie=UTF-8)
*  [Keycloak Dev Bookmarks](http://bookmarks.dev/search?q=keycloak) - Use the tag [keycloak](https://www.bookmarks.dev/tagged/keycloak)
*  [keycloak-config-cli Tool](https://github.com/adorsys/keycloak-config-cli)


# License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Thomas Darimont](https://github.com/thomasdarimont) has waived all copyright and related or neighboring rights to this work.
