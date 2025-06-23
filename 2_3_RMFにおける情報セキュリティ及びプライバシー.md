## 2.3 INFORMATION SECURITY AND PRIVACY IN THE RMF
## 2.3 RMFにおける情報セキュリティ及びプライバシー

---

**OMB CIRCULAR A-130: INTEGRATION OF INFORMATION SECURITY AND PRIVACY**  
**OMB通達A-130：情報セキュリティとプライバシーの統合**  

In 2016, OMB revised Circular A-130, the circular establishing general policy for the planning, budgeting, governance, acquisition, and management of federal information, personnel, equipment, funds, information technology resources, and supporting infrastructure and services. The circular addresses responsibilities for protecting federal information resources and managing personally identifiable information (PII). In establishing requirements for information security programs and privacy programs, the circular emphasizes the need for both programs to collaborate on shared objectives:  
* While security and privacy are independent and separate disciplines, they are closely related, and it is essential for agencies to take a coordinated approach to identifying and managing security and privacy risks and complying with applicable requirements. *
[OMB A-130] requires organizations to implement the RMF that is described in this guideline. 
With the 2016 revision to the circular, OMB also requires organizations to integrate privacy into the RMF process:  

2016年、米国行政管理予算局（OMB）は、連邦政府における情報、人員、設備、資金、情報技術資源、並びにそれらを支えるインフラやサービスの計画、予算、ガバナンス、調達、管理に関する基本方針を定めた通達「サーキュラーA-130」を改訂した。  

この通達は、連邦情報資源の保護および個人識別情報（PII）の管理に関する責任を明確にしている。情報セキュリティプログラムおよびプライバシープログラムに対する要件を定めるにあたり、両者が共通の目的に向けて連携する必要性が強調されている。  

---

セキュリティとプライバシーはそれぞれ独立した分野であるが、両者は密接に関連しており、各機関はこれらのリスクを一体的に把握・管理し、関連する法的・制度的要件を遵守するために、協調的なアプローチを取る必要がある。

---

[OMB A-130]は、すべての組織に対し、本ガイドラインで定義されているRMF（リスクマネジメントフレームワーク）の実施を義務付けている。また、2016年の改訂により、OMBはプライバシーの観点をRMFプロセス全体に組み込むことも組織に対して要求している。


* The RMF provides a disciplined and structured process that integrates information security, privacy, and risk management activities into the SDLC. This Circular requires organizations to use the RMF to manage privacy risks beyond those that are typically included under the “confidentiality” objective of the term “information security.” While many privacy risks relate to the unauthorized access or disclosure of PII, privacy risks may also result from other activities, including the creation, collection, use, and retention of PII; the inadequate quality or integrity of PII; and the lack of appropriate notice, transparency, or participation. *  

This section of the guideline describes the relationship between information security programs and privacy programs under the RMF. However, subject to OMB policy, organizations retain theflexibility to undertake the integration of privacy into the RMF in the most effective manner, considering the organization’s mission and circumstances.  

---

RMFは、情報セキュリティ、プライバシー、リスク管理に関する活動をSDLC（システム開発ライフサイクル）に統合するための、規律ある構造化されたプロセスである。本通達は、情報セキュリティという用語における「機密性（confidentiality）」の目標に通常含まれる範囲を超えて、より広範なプライバシーリスクの管理にもRMFを活用することを組織に求めている。  

多くのプライバシーリスクは、個人識別情報（PII）の不正アクセスや漏えいに起因するが、それに限られない。PIIの作成、収集、利用、保存といった取り扱いの過程、PIIの品質や完全性の欠如、さらには適切な通知や透明性、個人の関与が欠如していることなども、プライバシーリスクの要因となりうる。  

---

本ガイドラインの本節では、RMFにおける情報セキュリティプログラムとプライバシープログラムの関係性を明らかにする。ただし、OMBの方針に基づき、各組織には、自らのミッションや状況を踏まえて、プライバシーのRMFへの統合を最も効果的な方法で進める裁量が認められている。  


Executing the RMF requires close collaboration between information security programs and privacy programs. While information security programs and privacy programs have different objectives, those objectives are overlapping and complementary. Information security programs are responsible for protecting information and information systems from unauthorized access, use, disclosure, disruption, modification, or destruction (i.e., unauthorized system activity or behavior) in order to provide confidentiality, integrity, and availability. Privacy programs are responsible for ensuring compliance with applicable privacy requirements and for managing the risks to individuals associated with the creation, collection, use, processing, dissemination, storage, maintenance, disclosure, or disposal (collectively referred to as “processing”) of PII.30
When preparing to execute the steps of the RMF, organizations consider how to best promote and institutionalize collaboration between the two programs to ensure that the objectives of both disciplines are met at every step of the process.    

RMFを実行するには、情報セキュリティプログラムとプライバシープログラムの間で緊密な連携を図る必要がある。両プログラムはそれぞれ異なる目的を持つが、その目的は重なり合い、相互に補完する関係にある。

情報セキュリティプログラムは、機密性・完全性・可用性を確保するために、情報および情報システムを不正なアクセス、使用、開示、妨害、改ざん、破壊などの不正な活動から保護する責任を担う。

一方、プライバシープログラムは、法令等に定められたプライバシー要件への適合を確保するとともに、個人識別情報（PII）の作成、収集、利用、処理、配布、保存、維持、開示、廃棄といった一連の「処理」に伴い生じる、個人に対するリスクを管理する役割を担う。

RMFの各ステップを実行する準備段階において、組織は、両プログラムの連携をいかに効果的に促進し、組織内に定着させるかを検討する。これにより、プロセスのすべての段階において、情報セキュリティとプライバシーの双方の目的が確実に達成されることが求められる。  

When an information system processes PII, the organization’s information security program and privacy program have a shared responsibility for managing the risks to individuals that may arise from unauthorized system activity or behavior. This requires the two programs to collaborate when selecting, implementing, assessing, and monitoring security controls.31 However, while information security programs and privacy programs have complementary objectives with respect to managing the confidentiality, integrity, and availability of PII, protecting individuals’ privacy cannot be achieved solely by securing PII.  

情報システムが個人識別情報（PII）を処理する場合、不正なシステム活動や挙動によって個人にリスクが生じる可能性がある。そのリスクを管理する責任は、情報セキュリティプログラムとプライバシープログラムが共同で負うことになる。

このため、両プログラムは、セキュリティ制御の選定、実装、評価、監視の各段階において連携し、統一的に対応する必要がある。

ただし、両プログラムは、PIIの機密性・完全性・可用性の管理において補完的な役割を担うものの、PIIを安全に保護するだけでは、個人のプライバシー全体を守ることにはならない。

Not all privacy risks arise from unauthorized system activity or behavior, such as unauthorized access or disclosure of PII. Some privacy risks may result from authorized activity that is beyond the scope of information security. For example, privacy programs are responsible for managing the risks to individuals that may result from the creation, collection, use, and retention of PII; the inadequate quality or integrity of PII; and the lack of appropriate notice, transparency, or participation. Therefore, to help ensure compliance with applicable privacy requirements and to manage privacy risks from authorized and unauthorized processing of PII, organizations’ privacy programs also select, implement, assess, and monitor privacy controls.32  

すべてのプライバシーリスクが、PIIへの不正アクセスや開示といった不正なシステム活動・挙動から生じるわけではない。情報セキュリティの範囲を超えた、正当な業務活動によってもプライバシーリスクが発生する場合がある。  

たとえば、プライバシープログラムは、PIIの作成、収集、利用、保存といった処理によって個人に及ぶリスク、PIIの品質や完全性の欠如、さらには通知の不備、透明性の欠如、本人の関与が欠けていることなどから生じるリスクを管理する責任を担っている。  

したがって、法令等に基づくプライバシー要件の遵守を確保し、PIIの許可された処理および不正な処理の両方から生じるリスクに対応するために、組織のプライバシープログラムは、プライバシー制御の選定、実装、評価、監視といった管理活動を実施する必要がある。  

[OMB A-130] defines a privacy control as an administrative, technical, or physical safeguard employed within an agency to ensure compliance with applicable privacy requirements and to manage privacy risks. A privacy control is different from a security control, which the Circular defines as a safeguard or countermeasure prescribed for an information system or an organization to protect the confidentiality, integrity, and availability of the system and its information. Due to the shared responsibility that organizations’ information security programs and privacy programs have to manage the risks to individuals arising from unauthorized system activity or behavior, controls that achieve both security and privacy objectives are both privacy and security controls. This guideline refers to such controls that achieve both sets of objectives simply as “controls.” When this guideline uses the descriptors “privacy” and “security” with the term control, it is referring to those controls in circumstances where the controls are selected, implemented, and assessed for particular objectives.  

[OMB A-130]は、プライバシー制御を、適用されるプライバシー要件の遵守を確保し、プライバシーリスクを管理するために、機関内で導入される管理的・技術的・物理的な保護措置であると定義している。  

一方で、セキュリティ制御は、情報システムや組織に対して、システムおよびその情報の機密性、完全性、可用性を保護するために規定された保護策または対抗措置と定義されており、プライバシー制御とは異なる概念である。  

ただし、情報セキュリティプログラムとプライバシープログラムは、不正なシステム活動や挙動によって個人に生じるリスクを管理するという責任を共有している。そのため、セキュリティとプライバシーの両方の目的を同時に達成する制御は、「プライバシー制御」と「セキュリティ制御」の両方に該当する。  

本ガイドラインでは、両方の目的を兼ね備えたこうした制御を、単に「制御（control）」と呼ぶ。なお、「プライバシー制御」「セキュリティ制御」という用語が用いられる場合は、当該制御が特定の目的に応じて選定・実装・評価される文脈において用いられていることを意味する。  

The risk management processes described in this publication are equally applicable to security and privacy programs. However, the risks that security and privacy programs are required to manage are overlapping in some areas, but not in others. Consequently, it is important that organizations understand the interplay between privacy and security to promote effective collaboration between privacy and security officials at every level of the organization.  

本ガイドラインで示されるリスク管理プロセスは、セキュリティプログラムとプライバシープログラムの双方に等しく適用可能である。  
ただし、両プログラムが管理すべきリスクは、一部の領域では重複するが、その他の領域では明確に異なる。  

そのため、組織にとって重要なのは、プライバシーとセキュリティの相互関係を正しく理解し、組織のあらゆる階層において、プライバシー担当者とセキュリティ担当者の連携を効果的に促進することである。  