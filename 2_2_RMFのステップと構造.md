## 2.2 RISK MANAGEMENT FRAMEWORK STEPS AND STRUCTURE
## RMFのステップと構造

There are seven steps in the RMF; a preparatory step to ensure that organizations are ready to execute the process and six main steps. All seven steps are essential for the successful execution of the RMF. The steps are:   

RMF（リスクマネジメントフレームワーク）は、合計7つのステップで構成される。最初の「準備」ステップは、組織がこのプロセスを適切に実行できるよう体制を整えるものであり、続く6つが主要な手順となる。これら7つすべてが、RMFを効果的に機能させるために不可欠である。  

- Prepare to execute the RMF from an organization- and a system-level perspective by establishing a context and priorities for managing security and privacy risk.
- Categorize the system and the information processed, stored, and transmitted by the system based on an analysis of the impact of loss.26 
- Select an initial set of controls for the system and tailor the controls as needed to reduce risk to an acceptable level based on an assessment of risk. 
- Implement the controls and describe how the controls are employed within the system and its environment of operation. 
- Assess the controls to determine if the controls are implemented correctly, operating as intended, and producing the desired outcomes with respect to satisfying the security and privacy requirements. 
- Authorize the system or common controls based on a determination that the risk to organizational operations and assets, individuals, other organizations, and the Nation is acceptable. 
- Monitor the system and the associated controls on an ongoing basis to include assessing control effectiveness, documenting changes to the system and environment of operation, conducting risk assessments and impact analyses, and reporting the security and privacy posture of the system.   

各ステップの概要は以下のとおり：  

- 組織レベルおよびシステムレベルの両視点から、セキュリティおよびプライバシーに関するリスクを管理するための前提条件と優先事項を明確にし、RMF実行の準備を整える。

- 損失がもたらす影響の分析に基づいて、システムおよびそのシステムが処理・保存・送信する情報の重要度を分類する。

- リスク評価に基づいて、システムに対する初期のセキュリティ制御を選定し、必要に応じて調整（テーラリング）を行い、リスクを許容可能な水準まで低減する。

- 選定した制御を実装し、それらがシステムとその運用環境においてどのように機能しているかを明示する。

- 実装された制御が正しく構成され、想定どおりに動作し、セキュリティとプライバシーの要件を満たしているかを検証する。

- 組織の業務・資産・個人・他組織・国家に対するリスクが受容可能と判断された場合、システムや共通制御の運用を承認する。

- システムおよび関連する制御について、制御の有効性の継続的な評価、システムや運用環境の変更点の記録、リスク再評価や影響分析の実施、セキュリティとプライバシーの状況報告などを通じて、常時監視を行う。

Figure 2 illustrates the steps in the RMF. The RMF operates at all levels in the risk management hierarchy illustrated in Figure 1. Chapter Three provides a detailed description of each of the tasks necessary to carry out the steps in the RMF.   

図2は、RMFにおける各ステップの構成を視覚的に示している。RMFは、図1に示されたリスク管理階層のすべてのレベルで機能しており、組織全体から個々の情報システムに至るまで適用可能である。第3章では、これらのステップを実行する上で必要となる各タスクの内容が詳細に説明されている。  

fig.2  

While the RMF steps are listed in sequential order above and in Chapter Three, the steps following the Prepare step can be carried out in a nonsequential order. After completing the tasks in the Prepare step, organizations executing the RMF for the first time for a system or set of common controls typically carry out the remaining steps in sequential order. However, there could be many points in the risk management process where there is a need to diverge from the sequential order due to the type of system, risk decisions made by senior leadership, or to allow for iterative cycles between tasks or revisiting of tasks (e.g., during agile development). Once the organization is in the Monitor step, events may dictate a nonsequential execution of steps. For example, changes in risk or in system functionality may necessitate revisiting one or more of the steps in the RMF to address the change.   

RMFのステップは、上記および第3章において時系列順で示されているが、「準備（Prepare）」ステップ以降の手順については、必ずしも順番通りに実行する必要はない。システムまたは共通制御群に対して初めてRMFを適用する際、組織は通常、準備ステップを完了した後、残りのステップを順を追って実行する。しかし、システムの特性や上位組織によるリスク判断、あるいはアジャイル開発のようにタスクを反復または再実行する必要がある場合など、順序に従わずに進める必要が生じる場面も多い。  

一度「監視（Monitor）」ステップに入ると、その後の進行は必ずしも直線的ではなく、状況に応じて柔軟に対応する必要が出てくる。たとえば、リスクの変化やシステム機能の変更が発生した際には、それに対応するために、すでに完了したRMFステップの一部を再度実施しなければならない場合がある。  

---

**FLEXIBILITY IN RMF IMPLEMENTATION**   
**RMF実装の柔軟性**  
Organizations are expected to execute all steps and tasks in the RMF (apart from tasks labeled as optional). However, organizations have significant flexibility in how each of the RMF steps and tasks are carried out, as long as organizations are meeting all applicable requirements and effectively managing security and privacy risk. The intent is to allow organizations to implement the RMF in the most efficient, effective, and cost-effective manner to support mission and business needs in a way that promotes effective security and privacy. Flexible implementation may include executing tasks in a different (potentially nonsequential) order, emphasizing certain tasks over other tasks, or combining certain tasks where appropriate. It can also include the use of the Cybersecurity Framework to enhance RMF task execution.     

組織は、オプションとして明示されたものを除き、RMFのすべてのステップとタスクを実行することが求められる。ただし、組織は、関連するすべての要件を満たしつつ、セキュリティおよびプライバシーリスクを適切に管理している限り、それぞれのステップやタスクをどのように実施するかについて、広範な裁量を持つ。  
この柔軟性の目的は、ミッションや業務の要件を支援しつつ、セキュリティとプライバシーの実効性を高めるために、RMFを最も効率的かつ効果的、そして費用対効果の高い方法で実装できるようにする点にある。  

Flexibility of implementation can also be applied to control selection, control tailoring to meet organizational security and privacy needs, or conducting control assessments throughout the SDLC. For example, the selection, tailoring, implementation, and assessments of controls can be done incrementally as a system is being developed. The implementation of control tailoring helps to ensure that security and privacy solutions are customized for the specific missions, business functions, risks, and operating environments of the organization. In the end, the flexibility inherent in RMF execution promotes effective security and privacy that helps to protect the systems that organizations depend on for mission and business success and the individuals whose information is processed by those systems.   

柔軟な実施には、タスクを異なる（場合によっては非順序な）順番で実行すること、特定のタスクを優先的に扱うこと、あるいは状況に応じて複数のタスクを統合することが含まれる。また、RMFタスクの実行を強化する手段として、サイバーセキュリティフレームワーク（CSF）の併用も有効である。  

この柔軟性は、制御の選定や、組織のセキュリティ・プライバシー要件に応じた制御の調整（テーラリング）、ならびにSDLC（システム開発ライフサイクル）全体を通じた制御評価の実施にも適用できる。たとえば、制御の選定・調整・実装・評価は、システムの開発過程に合わせて段階的に進めることができる。  

制御をテーラリングすることで、各組織のミッションや業務機能、リスク、運用環境に最適化されたセキュリティおよびプライバシー対策を構築することが可能となる。最終的に、RMF実行に内在するこの柔軟性こそが、組織がその成功を支えるシステムおよびそれらによって取り扱われる個人情報を適切に保護するための、実効性あるセキュリティとプライバシーの実現につながる。  

Note: Since the RMF is an SDLC process that emphasizes ongoing authorization, organizations have the flexibility to determine which RMF step to enter (or reenter) based on an assessment of risk and the tasks described in the Prepare—System Level step. Determination of the appropriate RMF step requires an assessment of the current state of the system, a review of the activities that have already been completed for the system, identification of a proposed step and task entry into the RMF, a gap analysis to ensure that the risk is acceptable, documenting decisions, notifying stakeholders, and approval from the Authorizing Official (or other relevant decision maker).   

注：RMFは、継続的な承認を重視するSDLC（システム開発ライフサイクル）プロセスであるため、組織はリスク評価と「準備—システムレベル」ステップに定義されたタスクを踏まえて、どのRMFステップから着手（または再着手）するかを柔軟に判断できる。  
適切なステップへの移行を判断するには、以下の作業が必要となる：  
- 対象システムの現在の状態を評価すること
- すでに実施済みの活動内容を確認すること
- RMFにおいて着手すべきステップとタスクを明確にすること
- リスクが受容可能であることを確認するためのギャップ分析を行うこと
- 意思決定の内容を記録として残すこと
- 関係者に通知を行うこと
- 承認権限者（またはその他の適切な意思決定者）から正式な承認を得ること

---

Although the risk management approach in Figure 1 is conveyed as hierarchical, project and organization dynamics are typically more complex. The risk management approach selected by an organization may vary on a continuum from top-down command to decentralized consensus among peers. However, in all cases, organizations use a consistent approach that is applied to risk management processes organization-wide from the organization level to the information system level. Organizational officials identify and secure the needed resources to complete the risk management tasks described in this publication and ensure that those resources are made available to the appropriate personnel. Resource allocation includes funding to conduct risk management tasks and assigning qualified personnel that are needed to accomplish the tasks.   

図1に示されたリスク管理アプローチは階層的に描かれているが、実際のプロジェクトや組織の動態は、これよりもはるかに複雑である。組織が採用するリスク管理のアプローチは、上意下達の命令型から、対等な関係者同士による合意形成型まで、連続的なスペクトラム上で多様に変化しうる。  
それでもなお、すべての場合において、組織は組織レベルから情報システムレベルに至るまで、一貫したリスク管理アプローチを全体に適用する必要がある。  

組織の責任者は、本書で説明されているリスク管理タスクを実行するために必要なリソースを特定・確保し、それらを適切な担当者に行き渡らせる責任を負う。ここで言うリソースには、タスクを実行するための資金や、必要な資格や能力を持つ人材の配置などが含まれる。  

Each step in the RMF has a purpose statement, a defined set of outcomes, and a set of tasks that are carried out to achieve those outcomes. The outcomes can be achieved by different risk management levels—that is, some of the outcomes are universal to the entire organization, while others are system-focused or mission/business unit-focused. Figure 3 provides an example of the purpose statement and outcomes for the RMF Prepare step—Organization-Level.  

RMFの各ステップには、達成すべき目的、明確に定義された成果、一連の成果を実現するために必要なタスクがそれぞれ紐づいている。  
これらの成果は、リスク管理の実行レベルに応じて異なる形で実現される。すなわち、組織全体に共通する成果もあれば、個別のシステムや、ミッション・事業部門に特化した成果も存在する。
図3は、RMFにおける「準備」ステップ（組織レベル）の目的と成果の例を示している。  

fig.3  

Each task contains a set of potential inputs needed to execute the task and a set of expected outputs generated from task execution.27 In addition, each task describes the risk management roles and responsibilities associated with the task and the phase of the SDLC where task execution occurs.28 A discussion section provides information related to the task to facilitate understanding and to promote effective task execution. Finally, completing the RMF task description, there is a list of references to provide organizations with supplemental information for each task. Where applicable, the references also identify systems security engineering tasks that correlate with the RMF task.29 Figure 4 illustrates the structure of a typical RMF task.   

各タスクには、実行にあたって必要となる入力要素の集合と、実行の結果として得られる出力の集合が定義されている。  
さらに、各タスクには、それに関わるリスク管理上の役割と責任、および当該タスクが実施されるSDLC（システム開発ライフサイクル）上のフェーズが明示されている。  

「ディスカッション」セクションでは、タスク内容の理解を深め、円滑かつ効果的な実行を支援するための補足情報が示される。  
RMFタスクの説明の末尾には、各タスクに関する追加的な情報を参照できる文献リストが用意されている。該当する場合、これらの文献には、そのタスクと対応関係にあるシステムセキュリティエンジニアリング上のタスクも示されている。  

図4は、典型的なRMFタスクの構成要素を図解したものである。  

fig.4  

## 2.2 リスク管理フレームワークのステップと構造
## RMFのステップと構造

RMFには、組織がプロセスを実行する準備を整えるための準備ステップと、6つの主要ステップの合計7つのステップがあります。7つのステップはすべて、RMFを成功させるために不可欠です。ステップは以下の通りです：
- 組織レベルとシステムレベルの両方の視点から、セキュリティとプライバシーのリスクを管理するための文脈と優先順位を確立し、RMFの実行準備を行う。
- 損失の影響分析に基づき、システムおよびシステムで処理、保存、送信される情報を分類する。26
- システムのリスク評価に基づき、リスクを許容可能なレベルまで低減するために、システムに対する初期の制御措置を選択し、必要に応じて制御措置を調整する。
- 制御を実施し、システムとその運用環境内で制御がどのように適用されているかを説明する。 
- 制御が適切に実施され、意図したとおりに機能し、セキュリティとプライバシーの要件を満たす結果を生むかどうかを評価する。 
- 組織の運用と資産、個人、他の組織、および国家に対するリスクが許容可能であると判断した場合、システムまたは共通制御を承認する。 
- システムの有効性を評価し、システムおよび運用環境の変更を文書化し、リスク評価および影響分析を実施し、システムのセキュリティおよびプライバシーの状況を報告するなど、システムおよび関連する制御を継続的に監視する。

図 2 は、RMF のステップを示しています。RMF は、図 1 に示すリスク管理階層のすべてのレベルで機能します。第 3 章では、RMF のステップを実行するために必要な各タスクについて詳しく説明します。

図2

RMF のステップは、上記および第 3 章で時系列順に列挙されているが、準備ステップ以降のステップは時系列順以外の順序で実行することができる。システムまたは共通制御のセットに対して RMF を初めて実行する場合、組織は通常、準備ステップのタスクを完了した後、残りのステップを時系列順に実行する。ただし、システムのタイプ、上級管理職によるリスク決定、またはタスク間の反復サイクルやタスクの再検討（例：アジャイル開発中）を可能にするため、リスク管理プロセスにおいて順序から逸脱する必要が生じる点が多数存在します。組織がMonitorステップに入った後、イベントによりステップの非順序実行が求められる場合があります。例えば、リスクやシステム機能の変更により、変更に対応するためにRMFのステップの1つ以上を再検討する必要が生じる場合がある。  

---

RMF 実装の柔軟性
組織は、RMF のすべてのステップとタスク（オプションと指定されたタスクを除く）を実行することが期待されています。ただし、組織は、適用されるすべての要件を満たし、セキュリティとプライバシーのリスクを効果的に管理している限り、RMF の各ステップとタスクの実施方法について大幅な柔軟性を持っています。その目的は、組織がミッションとビジネス要件を支援し、効果的なセキュリティとプライバシーを促進する最も効率的、効果的、かつコスト効果の高い方法でRMFを実施できるようにすることです。柔軟な実施には、タスクを異なる（潜在的に非順序の）順序で実行すること、特定のタスクを他のタスクよりも重視すること、または適切な場合にタスクを組み合わせることが含まれます。また、RMFタスクの実行を強化するためにサイバーセキュリティフレームワークを使用することも含まれます。
実施の柔軟性は、制御の選択、組織のセキュリティとプライバシーの要件を満たすための制御の適応、またはSDLC全体での制御評価の実施にも適用できる。例えば、制御の選択、適応、実施、および評価は、システムの開発過程で段階的に実施できる。制御の適応の実施は、組織の特定のミッション、ビジネス機能、リスク、および運用環境に合わせてセキュリティとプライバシーのソリューションをカスタマイズすることを確保する。最終的に、RMF 実行に内在する柔軟性は、組織がミッションとビジネスの成功に依存するシステム、およびそれらのシステムによって処理される個人の情報を保護する効果的なセキュリティとプライバシーを促進する。
注：RMF は継続的な承認を重視する SDLC プロセスであるため、組織はリスクの評価と「準備—システムレベル」ステップで説明されているタスクに基づいて、どの RMF ステップに入る（または再入る）かを柔軟に決定することができる。適切なRMFステップの決定には、システムの現在の状態の評価、システムに対して既に完了した活動のレビュー、提案されたステップとタスクのRMFへの入力、リスクが受け入れ可能であることを確認するためのギャップ分析、決定の文書化、関係者の通知、および承認権限者（またはその他の関連する意思決定者）の承認が必要だ。

---

図1で示されるリスク管理アプローチは階層的として示されているが、プロジェクトや組織のダイナミクスは通常より複雑だ。組織が選択するリスク管理アプローチは、トップダウンの命令からピア間の分散型合意まで、連続体上で変動する可能性がある。ただし、いずれの場合も、組織は組織レベルから情報システムレベルまで、組織全体に適用される一貫したアプローチを使用する。組織の担当者は、本資料で説明されるリスク管理タスクを完了するために必要なリソースを特定し確保し、それらのリソースが適切な人員に提供されることを確認する。リソースの配分には、リスク管理タスクを実施するための資金提供と、タスクを遂行するために必要な資格を有する人員の配置が含まれる。

RMF の各ステップには、目的記述、定義された一連の成果、およびそれらの成果を達成するために実施される一連のタスクがある。成果は、さまざまなリスク管理レベルによって達成することができる。つまり、成果の中には、組織全体に共通のものもあれば、システムに焦点を当てたものや、ミッション/事業部門に焦点を当てたものもある。図 3 は、RMF の「準備」ステップ（組織レベル）の目的記述と成果の例を示している。

図 3

各タスクには、タスクを実行するために必要な潜在的な入力のセットと、タスクの実行から生成される期待される出力のセットが含まれます。27 さらに、各タスクでは、タスクに関連するリスク管理の役割と責任、およびタスクの実行が行われるSDLCのフェーズが説明されています。28 議論セクションでは、タスクの理解を促進し、効果的なタスク実行を促進するための関連情報が提供されています。最後に、RMF タスクの説明を完了すると、各タスクに関する補足情報を組織に提供するための参照リストがある。該当する場合、参照には、RMF タスクと関連するシステムセキュリティエンジニアリングタスクも特定される。29 図 4 は、典型的な RMF タスクの構造を示している。 

図 4

