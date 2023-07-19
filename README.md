# I2NSF-Closed-Loop-Security-Control

The Closed-Loop Security Control provides Intent Assurance by utilizing Interface to Network Security Functions (I2NSF) Framework.

The [IETF (Internet Engineering Taskforce)](https://www.ietf.org/) 
[I2NSF (Interface to Network Security Functions) workgroup](https://datatracker.ietf.org/wg/i2nsf/charter/)
the working group aims to define software interface specifications for functions that
ensure network integrity, confidentiality, and availability so that one implementor
can translate well-defined user requirements into enforceable policies.

The programs in this repository are related to the following documents:

* I2NSF Capability YANG Data Model
 [draft-ietf-i2nsf-capability-data-model-32](https://datatracker.ietf.org/doc/draft-ietf-i2nsf-capability-data-model/)
 
  - This document gives the motivation for controlling access policies in a data center setup from a single management point
  This can make it efficient to manage multiple devices which may be changed. An XML-type schema is described for 
  controlling network traffic according to protocol, port, originating IP address, etc.
 
* Consumer-Facing Interface YANG Data Model
 [draft-ietf-i2nsf-consumer-facing-interface-dm-31](https://datatracker.ietf.org/doc/draft-ietf-i2nsf-consumer-facing-interface-dm/)
 
  - This document specifies what policies should be available in a friendly interface for the operator. It uses an XML
  schema that can be used to create a web interface. Firewalls, DDoS prevention, and time-based access to internet
  resources are considered.

* NSF-Facing Interface YANG Data Model
 [draft-ietf-i2nsf-nsf-facing-interface-dm-29](https://datatracker.ietf.org/doc/draft-ietf-i2nsf-nsf-facing-interface-dm/)
 
  - This document allows vendors to specify how policies should be enforced on their hardware so that one obtains consistent
  behavior. It allows for different types of actions based on both applied system policies and in response to external events 
  such as attacks. 

* Registration Interface YANG Data Model
 [draft-ietf-i2nsf-registration-interface-dm-26](https://datatracker.ietf.org/doc/draft-ietf-i2nsf-registration-interface-dm/)
 
  - This document allows for querying the NSF capabilities from a single interface.

* Security Policy Translation in I2NSF
 [draft-yang-i2nsf-security-policy-translation-13](https://datatracker.ietf.org/doc/draft-yang-i2nsf-security-policy-translation/)
 
   - This document describes a possible means by which a high-level policy (e.g., preventing access to particular types of websites) 
   can be translated to low-level policy implementations.
   
* Monitoring Interface YANG Data Model
 [draft-ietf-i2nsf-nsf-monitoring-data-model-20](https://datatracker.ietf.org/doc/draft-ietf-i2nsf-nsf-monitoring-data-model/)
 
   - This document proposes an information model and the corresponding YANG data model for monitoring Network Security Functions 
   (NSFs) in the Interface to Network Security Functions (I2NSF) framework.
   
* Analytics Interface YANG Data Model
 [draft-lingga-i2nsf-analytics-interface-dm-01](https://datatracker.ietf.org/doc/draft-lingga-i2nsf-analytics-interface-dm/)
 
   - This document proposes an information model and the corresponding YANG data model for analytics (Reconfiguration and Feedback Information)
   information to enhance the security posture.
