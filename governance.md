# **Governance Structure**

This document describes the formal governance structure of the CVXPY project. For the purpose of this document, “CVXPY” includes all repositories in the [CVXPY GitHub organization](https://github.com/cvxpy).


## **Mission**

The CVXPY project provides a domain-specific language for convex optimization in the Python programming language. Our mission is to improve the accessibility and expand the scopes of third-party convex optimization solvers. We prioritize the experiences of lay people, while striving for the efficiency and extensibility that optimization experts expect of an advanced modeling language.


## **Code of Conduct**

The CVXPY community strongly values inclusivity and diversity. Everyone should treat others with the utmost respect. Everyone in the community must adhere to the Code of Conduct specified in [the CVXPY GitHub repository](https://github.com/cvxpy/cvxpy/blob/master/CODE_OF_CONDUCT.md). Violations of this code of conduct may be reported confidentially to Project Maintainers indicated at that link. 


## **Entities**

This section outlines the different entities that exist within the CVXPY project, their basic role, and how membership of each entity is determined.


### **Benevolent Dictator For Life**

Due to his role in the creation of CVXPY, [Steven Diamond](https://stevendiamond.me/) holds the title of [Benevolent Dictator For Life (BDFL)](https://en.wikipedia.org/wiki/Benevolent_dictator_for_life).


### **Project Maintainers**

Project Maintainers lead the technical development of the CVXPY project, and they are the ultimate authority on the direction of the CVXPY project. The current Project Maintainers are:



*   Steven Diamond ([@SteveDiamond](https://github.com/SteveDiamond))
*   Akshay Agrawal ([@akshaya](https://github.com/akshayka))
*   Riley Murray ([@rileyjmurray](https://github.com/rileyjmurray/))
*   Bartolomeo Stellato ([@bstellato](https://github.com/bstellato))

A new maintainer may be added by consensus of the current Project Maintainers  and notification to the Steering Committee.

Before becoming a maintainer, it is expected that the community member will have been an active participant in the development and maintenance of the CVXPY repository for a sustained period of time. This includes triaging issues, proposing and reviewing pull requests, and updating any binary dependencies as needed.


### **Emeritus Project Maintainers**


Emeritus Project Maintainers are community members who were Project Maintainers, but have stepped back to a less active role. A Project Maintainer may choose to switch to emeritus status by informing the other Project Maintainers and the Steering Committee.


### **Steering Committee**

The Steering Committee supports the Project Maintainers by representing CVXPY in all administrative and legal capacities. In addition, the Steering Committee:



*   Approves expenditures related to CVXPY.
*   Negotiates and approves contracts with external contractors who provide paid work to CVXPY.

The current members of the Steering Committee are:



*   Stephen Boyd ([Stanford](https://web.stanford.edu/~boyd/))
*   Steven Diamond ([BlackRock AI](https://stevendiamond.me/))
*   Akshay Agrawal ([Stanford](https://www.akshayagrawal.com/))
*   Bartolomeo Stellato ([Princeton](https://stellato.io/))
*   Riley Murray ([Berkeley](https://rileyjmurray.wordpress.com/))

A member of the Steering Committee may leave the committee by notifying the Steering Committee and Project Maintainers. The remaining Steering Committee members, in consultation with the Project Maintainers, will invite a member of the community to join in order to maintain a quorum of five members.


## **Decision Making Process**

This section outlines how financial and non-financial decisions are made in the CVXPY project.


### **Financial Decisions**

All financial decisions are made by the Steering Committee to ensure any funds are spent in a manner that furthers the mission of CVXPY. Financial decisions require majority approval by Steering Committee members.

Community members proposing decisions with a financial aspect should contact the Steering Committee directly.


### **Non-financial Decisions**

All non-financial decisions are made via consensus of the Project Maintainers. Emeritus Project Maintainers are not considered to be Project Maintainers for this purpose.

Code-related decisions, such as when a pull request is ready to be accepted and merged, should be discussed via the relevant GitHub issues and pull requests. If consensus cannot be achieved, the community member proposing the change may be invited by a project maintainer to present their proposal at a developer call for further discussion and community input.

Changes to any public API require explicit approval (in the form of an "Approval" on a GitHub review) from at least half of the Project Maintainers.

Non-code-related decisions, such as long-term strategic planning for CVXPY, should either be discussed in a GitHub issue, or tabled as an agenda item and discussed on a developer call.

If consensus on a non-financial decision cannot be achieved, the final decision will be made by the BDFL.

The Steering Committee can gain additional decision-making power if the Project Maintainers decide to delegate.


### **Conflict of Interest**

It is expected that community members will be employed at a wide range of companies, universities and non-profit organizations. Because of this, it is possible that members will have conflicts of interest. Such conflicts of interest include, but are not limited to:



*   Financial interests, such as investments, employment or contracting work, outside of CVXPY that may influence their work on CVXPY.
*   Access to proprietary information of their employer that could potentially leak into their work with CVXPY.

All members of the Steering Committee shall disclose to the Steering Committee any conflict of interest they may have. Members with a conflict of interest in a particular issue may participate in Steering Committee discussions on that issue, but must recuse themselves from voting.

Project Maintainers and repository maintainers should also disclose conflicts of interest with other Project Maintainers and step back from decisions when conflicts of interests are in play.


## **GitHub Permissions**

GitHub permissions are used to control access to the CVXPY GitHub repository.

Anyone with commit access to the repository is trusted to use it in a way that is consistent with the Decision Making Process. Those with permissions should prefer pull requests over direct pushes, ask for feedback on changes if they are not sure there is a consensus, and follow CVXPY’s [style guide](https://github.com/cvxpy/cvxpy/blob/master/CONTRIBUTING.md#code-style) and development processes.


### **Project Maintainers**

Project Maintainers are added as [Owners](https://docs.github.com/en/free-pro-team@latest/github/setting-up-and-managing-organizations-and-teams/permission-levels-for-an-organization#permission-levels-for-an-organization) of the CVXPY GitHub organization.


### **Emeritus Project Maintainers**

Emeritus Project Maintainers retain the same commit rights as Project Maintainers, unless they choose to surrender them.


## **Community Involvement**

The CVXPY project highly values the contributions made by members of the community. As an open-source project, CVXPY is both made for the community, and by the community.

There are four main channels that CVXPY uses to engage with the community.


### **Community Forums**

The CVXPY Project Maintainers operate a [Google Group](https://groups.google.com/g/cvxpy) and host [GitHub Discussions](https://github.com/cvxpy/cvxpy/discussions) within the CVXPY repository. These forums serve two purposes. First, they provide a space for users to seek advice on how to use CVXPY (or convex optimization more broadly) in their intended application. Second, they provide a space for discussion on possible improvements to CVXPY or its dependencies.


### **Discord Server**

Discussions focused on CVXPY’s development are conducted on a [Discord Server](https://discord.gg/k4Aq8cA8AZ). The server is public but requires email verification.

The server consists of several channels with different permissions based on the concept of Discord roles. The named roles are “Project Maintainer” and “Contributor.” The Project Maintainers have write access to all channels and also have a private channel. Those with the “Contributor” role have write access to the “developers” channel, which is otherwise read-only. 

Individuals who have contributed significantly to the development of CVXPY, for example by proposing and merging at least one substantial pull request, may be invited to the Discord server as Contributors. Project Maintainers may grant the Contributor role within Discord at their discretion, and may create additional channels for specific long-term projects in CVXPY’s development.


### **Developer Calls**

The Steering Committee hosts quarterly developer calls to discuss CVXPY-related business. 

The precise time of a given call is determined one month ahead of time by discussions on the “developer-calls” channel of the CVXPY Discord Server. 
