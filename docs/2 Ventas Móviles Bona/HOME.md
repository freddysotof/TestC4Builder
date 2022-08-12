# 2 Ventas Móviles Bona

![diagram](https://www.plantuml.com/plantuml/svg/0/ZLPDRnit4BqRy7zWVQaCk1OGj9USOYjoxDHAL4jssfCnont9XBdaXkHAKOh-e1nwA7phLN-iC-JkIYj_f3vON78uy-RDuv1lV00NgaBlx_sWZDHLZk8kXDA_xlSTB8_dAjnLMUNHIMi2cd0iRT67t2am2rsLLN_myqzZ3IPSZoxx6WBwG5Et0x86PT0Tbz7v_jxboHyVhwUtdowcvxUNmtV33szxXpm_HkUjwSdAXoDnCD2AWk013Q-DaEbB4AYn-leL76gj-bC78LX283vNlEOH1A4g7JXH6H0UCcSzY9At71ySjZ4Aoe8SZ-W7ShGSX73ErBnov06A4jR_WETev5HM5DfwiIBVjOrKwmV3owMpUILfTTkxb3b-OPUWjHWmRiSHtX8Wd5Ugu5Ii0A4fnFh1vMZG2nJ4kgAnL3HDaPgSa-iVnMJb0nOzA4loTLAMMqImTufTA6A8t1BMPc-NC4fXGvdbm3LHaQ0ZiK0dK8i2pVfVikLFnfWh7nHLqPDh2Lhbn5b2rHRtTlWbzAIsLHvBHx_Yh38oA6iyepjJ3ZFmiPnZPqlh92s1c94H3w9J0gi5vKUXqIpMVrj6tsQosd15smbahg91YK6n3vf_F_dueNy-dOuZk4HOHEOWonIhwYeEHhynZf6If0vq2zuUGraDkplbgtkcUtmX1gz-vLqN16PEAcd1m0v7lfALyw1toT-ezL6CEmYPZQAdqQaD7EUKs8e21DOUCrERRRdS4brqHA5fvwG5m7wkKAeCErexYb-bmn8eaHLz9Rv1W6xutiPuQYkJWrlr5aL67cymvZbQFomKPtbAzJiu57_kxmdwQoNHMvAY3ZvX9aYiMabWCJ2Yum_3gVX5Z6u6kshGpmaY0crFdoFCXStLZ9mcXHAYfChDZYs9Q65WWNF8QMw9MKoj2zMNZ7MYp5nJoM2EkvYl46HuF-7XJSH6Q9n3IyS5PN3K3PIqmWf7NGyoccCrcU2eYDH9KlcsYEr6XrBL6ejKjXJjqbEilmMRanfOufD42XLEHK8SrravwY8pwufDXtfCpqbpmdXZnpprZbhAD6eE1ns-FZMio4XzrCWpjJM9hcvztOpkB0adtqfAdCSPCOaUap9ZagSWx-UE1TPPcpJ74aricYQtegJBnSPENwkrJXexIJo19izspnE767foLG3vq90a9tgJpph2G7V89kygS5JgfoZTdFSDkPqB8hB4O0s9mQi08b7Vual_hr2d-hSjQXYJu_1jEviqUrhhcD8b8XVIIwSoLaBCYj24rPc30fVMtG-imqURcpxTH7efK7rJ9jDQzB50e-duiUFwudlMUcDVfziAvNjPDuQf7myR0H3Xlj9CBfsxK4LTDctksSHQNstVVO69pJRkP-ceNliNaCPUyZ_iqZidTPxQS6F3PljxV-tliMMgmV8fm-WeiVxyEb6MReRktKNf_ZwwRAoYHVtsgkdLzIE134yMofSa__GKYVRpNVCe_krp4XzEXAfjYitJ9-zsHsukC-gl_FYA5tgkShk959RVZHHGhx_Dh8cxtg39urFpFm00)

**Level 2: Container diagram**

Once you understand how your system fits in to the overall IT environment, a really useful next step is to zoom-in to the system boundary with a Container diagram. A "container" is something like a server-side web application, single-page application, desktop application, mobile app, database schema, file system, etc. Essentially, a container is a separately runnable/deployable unit (e.g. a separate process space) that executes code or stores data.

The Container diagram shows the high-level shape of the software architecture and how responsibilities are distributed across it. It also shows the major technology choices and how the containers communicate with one another. It's a simple, high-level technology focussed diagram that is useful for software developers and support/operations staff alike.

**Scope**: A single software system.

**Primary elements**: Containers within the software system in scope.
Supporting elements: People and software systems directly connected to the containers.

**Intended audience**: Technical people inside and outside of the software development team; including software architects, developers and operations/support staff.

**Notes**: This diagram says nothing about deployment scenarios, clustering, replication, failover, etc.