# 1 App Pizzarelli

![diagram](https://www.plantuml.com/plantuml/svg/0/XLRDRXit4BuBq3kmkaG65ElINdgAxIYE2qSM8hbfJyRiab8cu99RaYj7Blf0FlHG-17qOfsPNMrMYXmB0hHUpi_tpJSpz9kO8AIgiFtUJ-XoMscZFgTKnb_7um3tfojCdwkiYYRatYNZqcdkYp7eWE3MjYghySNFhsSMNBhzS3ssa4nCzEhkWgm1dGcdfGJlzwxF_hovNTnzkbgylxkUN4wcRuSd_7vcGlHkc5SnZTJWmY8bCGDwl7Kgh_zI16g63myGZBKuNWH8oHC2zLV5Pz608bHbWA0g1of25dm4LRBBwO2op3SncU9kyZKDqps5NjoZHSz9vYQiCKVFAOnRR_-Lfm8T5iP5-6AYCb-J2SuV1eehSNVwCg1-FbJkGp3-kI3mK5boFQCVzSba76OMV6u8lR6gX9N4iA1yqCOfhu9POKm15CdsnIIG567xg37LmL-fElnmNMGKxNUg7qJrOVkqHajaphq3pZ9XW42H8o5qIrnL0GYx8nD9IBHTGWrKNNLMbftogms1o36ZoaFoR6vRdJPg-yH0JHGiRHFKN4jaghEh5iJfTB9GlpIaInyO0AXY-vYyfiZl5ulPd8f0RAcUIEesgJ4eT4iV2eAyVNBV8sPCZ7gpSzmp9zgCc-g8ZXd4HhYeDcEleBIOTsf1kkM6-gahtRcld8Qm8KubSzehqE14_TtlAVgq_8S5Y5aTcJ7KWZ3rA-ymFwm1ARwid3nRvYICA9aY2rKONNSPKIXzn8HhmbxuMk4Xtin7wipfu56V2EfzB9hxuXoYZ9LeA0qHQPWAK8vxp4ATMWtVOQ29zi6SiD5b1K73OV7jhYjzjnb6HpLATAOXZgZeEOUb9n8ihmmhCMhRPzJjojPTIRbDoe-mogslj2mG-bNlg7Y9A0Wrvf0HtyCY7w_mfZkyDPNOQUnz1KgJi6cLt-Otqp6th82huNqqLgJVWRkDqlUjwNp7WmqRetfCclay0c0m-h6_o7jjU1Yfi04pdfuNiyessoMLbVMYYspIngMpC5ycME-yWpttl5jjlolXr2TSqXWHkGHwjnvf8rBoN7hbUAHNNGZSOBAxQMcyBW1j_96JA59aKGGqOle7NNRVBEjlQtzFYiUI9_wjiRYc-sq_dfnzQmbpD7c_zq-_9v3bOfG5qhJF57ZYsKoYaNBDvTdgHwFJ7JmPBmh0emoPfHLQS5irzvEZuaMp_Gza_IqXJpHrTNDhr6qUblk5FCdOxUFIErzVHEnLPlck6C9q_w3u_ZrB8sVx-gWaGT_GE_b_udy0)

**Level 2: Container diagram**

Once you understand how your system fits in to the overall IT environment, a really useful next step is to zoom-in to the system boundary with a Container diagram. A "container" is something like a server-side web application, single-page application, desktop application, mobile app, database schema, file system, etc. Essentially, a container is a separately runnable/deployable unit (e.g. a separate process space) that executes code or stores data.

The Container diagram shows the high-level shape of the software architecture and how responsibilities are distributed across it. It also shows the major technology choices and how the containers communicate with one another. It's a simple, high-level technology focussed diagram that is useful for software developers and support/operations staff alike.

**Scope**: A single software system.

**Primary elements**: Containers within the software system in scope.
Supporting elements: People and software systems directly connected to the containers.

**Intended audience**: Technical people inside and outside of the software development team; including software architects, developers and operations/support staff.

**Notes**: This diagram says nothing about deployment scenarios, clustering, replication, failover, etc.