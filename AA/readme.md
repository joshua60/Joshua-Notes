# 認證與授權管理服務
1. Google授權服務論文 : Google Zanzibar Policy Framework, 基於Zanzibar的授權框架而開發的授權系統
    * Ory的Keto 實現Zanzibar的存取策略
    * SpiceDB: CNCF的專案，其官網 與 Github.
    * https://zanzibar.academy/  by Okta  提供雲SaaS
    * OSO: 使用度廣，Oso Cloud, Oso’s authorization-as-a-service.
2. Cloud Identity Infrastructure and Services 
    * 服务商介绍与研究报告 https://solutionsreview.com/identity-management/the-30-best-identity-management-companies/
    * 集成的案例过程与说明：https://charmed-kubeflow.io/docs/authentication
3. Cloud Native Open Source Identity Infrastructure and Services
    * ORY ：Golang Zero Trust Base
        * 官网文件 https://www.ory.sh/kratos/docs/
        * 新官网 https://www.ory.sh/  与更新的ECO System
            * Ory Kratos: Identity and User Infrastructure and Management. Ory Kratos is a fully customizable, API-only platform for login, two-factor authentication, social sign-in, passwordless flows, registration, account recovery, email / phone verification, secure credentials, identity and user management.
            * Ory Hydra: OAuth2 & OpenID Connect Server.   Ory Hydra is an API-only, "headless," OAuth 2.0 and OpenID Connect provider that can interface with any identity and user management system, such as Ory Kratos, Firebase, your PHP app, LDAP, SAML, and others.
            * Ory Oathkeeper: Identity & Access Proxy.  Ory Oathkeeper is a zero trust networking proxy and sidecar for popular ingress services and API gateways. It checks if incoming network request are authenticated and allowed to perform the requested action.
            * Ory Keto: Access Control Policies as a Server.  Ory Keto is the world's first and leading open-source implementation of Google's Zanzibar research paper, an infinitely scalable and blazing fast authorization and permissioning service - RBAC on globally distributed steroids.
        * 官网 https://www.ory.sh/  与2020年的ECO System
            * ORY Kratos ：an API-first Identity and User Management system
            * ORY Hydra：an OpenID Certified™ OAuth2 and OpenID Connect Provider can connect to any existing identity database (LDAP, AD, KeyCloak, PHP+MySQL, ...) and user interface.
            * ORY Oathkeeper：a BeyondCorp/Zero Trust Identity & Access Proxy 
            * ORY Keto：a policy decision point.
            * ORY Fosite (以Hydra為實現前端)：an extensible security first OAuth 2.0 and OpenID Connect SDK for Go.
            * ORY Ladon （3年沒維護功能置入Keto）：a library written in Go for access control policies, similar to Role Based Access Control or Access Control Lists.
            * ORY Dockertest：
    * Pomerium:  Golang Zero Trust Base
        * 官网：https://www.pomerium.com/
        * Github: https://github.com/pomerium/pomerium
            * For K8S 积极开发中 https://github.com/pomerium/pomerium-operator

    * ForgeRock：Java Based提供open source version, 维护量不大
        * 免费的Community Version:  https://github.com/ForgeRock
        * Open Community: https://forgerock.org/
        * 官网： https://www.forgerock.com/

