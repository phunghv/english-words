# new-words.md

Word data file for **Learn English Word** app.
Push this file (and `words-version.txt`) to your public GitHub repo.

---

## Format

Each word block starts with `## <word>`, followed by attribute lines.

### Inline styling (supported in `usage` and `example`)

| Syntax | Renders as |
|---|---|
| `==text==` | Highlighted — accent color + semi-bold |
| `**text**` | Bold |
| `*text*` | Italic |

### Single-line

```
## word
- phonetic: /IPA/
- difficulty: 1
- categories: communication, planning
- meaning: Vietnamese
- definition: English definition
- usage: single grammar note
- example: one example sentence
```

### Multi-line `usage` / `example` / `categories`

```
- categories:
  - communication
  - collaboration
- usage:
  - line 1
  - line 2
- example:
  - Sentence one.
  - Sentence two.
```

---

<!-- Words below — 100 office & software company vocabulary -->

## acknowledge
- phonetic: /əkˈnɒlɪdʒ/
- difficulty: 2
- categories: communication, collaboration
- meaning: thừa nhận, xác nhận đã nhận được
- definition: to accept or confirm that something is true, or that a message has been received
- usage:
  - **V + O** (transitive): ==acknowledge== a message / issue / contribution
  - **V + that-clause**: "I acknowledge that the deadline was missed."
  - **V2/V3**: *acknowledged* / *acknowledged*
  - Kết hợp phổ biến: *formally* acknowledge, *publicly* acknowledge
- example:
  - Please ==acknowledge== receipt of this email so we know the specs have been delivered.
  - The CTO ==acknowledged== the team's effort in shipping the feature before the deadline.

## actionable
- phonetic: /ˈækʃənəbl/
- difficulty: 2
- categories: analysis, planning
- meaning: có thể thực hiện ngay, khả thi, cụ thể
- definition: clear and specific enough to be acted on immediately
- usage:
  - **Tính từ** đứng trước danh từ hoặc sau *be*: ==actionable== feedback / insights / steps
  - Phổ biến trong tech: "Make your comments ==actionable==."
  - Trái nghĩa: *vague*, *abstract*
- example:
  - Instead of saying "improve performance," please give ==actionable== suggestions with specific metrics.
  - The retrospective produced three ==actionable== items that the team committed to in the next sprint.

## address
- phonetic: /əˈdres/
- difficulty: 1
- categories: execution, planning
- meaning: giải quyết, đề cập đến, xử lý (vấn đề)
- definition: to deal with or speak about a problem, issue, or concern
- usage:
  - **V + O** (transitive): ==address== a problem / concern / issue / bug
  - Không dùng với giới từ trong nghĩa này: ~~address to a problem~~
  - **V2/V3**: *addressed* / *addressed*
  - Kết hợp: *fully* address, *directly* address, *fail to* address
- example:
  - The hotfix was deployed to ==address== the authentication bug affecting production users.
  - We need to ==address== the scalability concerns before the product reaches 1 million users.

## agenda
- phonetic: /əˈdʒendə/
- difficulty: 1
- categories: meetings, collaboration
- meaning: chương trình nghị sự, danh sách nội dung cuộc họp
- definition: a list of items to be discussed or acted on in a meeting
- usage:
  - **Danh từ đếm được**: *an* agenda, *the* agenda, *agendas*
  - Giới từ: ==on the agenda== ("Is this on the agenda?"), *set the agenda*
  - Kết hợp: *meeting* agenda, *hidden* agenda, *set / follow / stick to* the agenda
- example:
  - Please send the ==agenda== at least 24 hours before the sprint planning meeting.
  - Migrating to the new CI/CD pipeline is the first item ==on the agenda== for today's all-hands.

## agile
- phonetic: /ˈædʒaɪl/
- difficulty: 2
- categories: collaboration, communication
- meaning: linh hoạt, nhanh nhẹn; phương pháp Agile
- definition: able to move and adapt quickly; also refers to the Agile software development methodology
- usage:
  - **Tính từ**: an ==agile== team / approach / mindset
  - Danh từ (viết hoa): work in ==Agile==, adopt ==Agile==
  - Kết hợp: ==Agile== methodology, ==Agile== sprint, *cross-functional* agile team
- example:
  - Our team follows ==Agile== with two-week sprints and daily stand-ups.
  - An ==agile== approach allowed us to pivot quickly when the client changed the requirements mid-project.

## align
- phonetic: /əˈlaɪn/
- difficulty: 2
- categories: collaboration, communication
- meaning: thống nhất, đồng bộ hóa, phối hợp hướng đi
- definition: to make sure that goals, priorities, or teams are in agreement and working toward the same direction
- usage:
  - **V + with**: ==align== with the strategy / roadmap / stakeholders
  - **V + on**: ==align== on priorities / requirements / timelines
  - **V2/V3**: *aligned* / *aligned*
  - Tính từ: *be aligned*, *get aligned*, *stay aligned*
- example:
  - We need to ==align== with the product team on the acceptance criteria before development starts.
  - Make sure the engineering roadmap is ==aligned== with the company's Q3 objectives.

## allocate
- phonetic: /ˈæləkeɪt/
- difficulty: 2
- categories: planning, execution
- meaning: phân bổ, phân phối (nguồn lực, ngân sách, thời gian)
- definition: to distribute or assign resources, time, or responsibilities for a specific purpose
- usage:
  - **V + O + to**: ==allocate== resources / budget / tasks *to* a team / person
  - **V2/V3**: *allocated* / *allocated*
  - Kết hợp: ==allocate== bandwidth, ==allocate== headcount, *appropriately / evenly* allocate
- example:
  - The project manager ==allocated== two senior engineers to the payment integration module.
  - We need to ==allocate== more testing resources before the production release.

## approve
- phonetic: /əˈpruːv/
- difficulty: 1
- categories: execution, planning
- meaning: phê duyệt, chấp thuận
- definition: to officially agree to or accept something such as a plan, request, or document
- usage:
  - **V + O**: ==approve== a PR / design / budget / request
  - **V2/V3**: *approved* / *approved*
  - Danh từ: *approval* — "pending ==approval==", "get ==approval== from"
  - Thụ động phổ biến: "The RFC was ==approved== by the architecture committee."
- example:
  - The pull request has been reviewed and ==approved== by two senior engineers.
  - The budget for the new data infrastructure must be ==approved== by the VP of Engineering.

## architecture
- phonetic: /ˈɑːkɪtektʃər/
- difficulty: 2
- categories: engineering, execution
- meaning: kiến trúc hệ thống, cấu trúc tổng thể
- definition: the high-level structure and design of a software system, including components and their relationships
- usage:
  - **Danh từ không đếm được** (khi nói chung): good ==architecture==
  - **Danh từ đếm được** (khi cụ thể): *a* microservices ==architecture==
  - Kết hợp: *system / software / cloud / microservices / monolithic* ==architecture==
  - Động từ liên quan: *design*, *define*, *review* the ==architecture==
- example:
  - The team decided to move from a monolithic ==architecture== to microservices to improve scalability.
  - We held an ==architecture== review session before starting the new data pipeline.

## assign
- phonetic: /əˈsaɪn/
- difficulty: 1
- categories: execution, planning
- meaning: giao việc, phân công nhiệm vụ
- definition: to give someone a task, role, or responsibility
- usage:
  - **V + O + to**: ==assign== a task / ticket / role *to* someone
  - **V + O**: ==assign== responsibilities / ownership
  - **V2/V3**: *assigned* / *assigned*
  - Bị động: "The bug was ==assigned== to the backend team."
- example:
  - Please ==assign== the critical bug tickets to the on-call engineer immediately.
  - Each feature should be ==assigned== a clear owner to avoid confusion during the sprint.

## benchmark
- phonetic: /ˈbentʃmɑːk/
- difficulty: 2
- categories: engineering, execution
- meaning: chuẩn đối sánh, tiêu chuẩn đánh giá hiệu suất
- definition: a standard or point of reference used to measure and compare performance
- usage:
  - **Danh từ**: set a ==benchmark==, use as a ==benchmark==
  - **Động từ**: ==benchmark== the system / performance / competitors
  - **V2/V3**: *benchmarked* / *benchmarked*
  - Kết hợp: *industry* ==benchmark==, *performance* ==benchmark==, run a ==benchmark== test
- example:
  - We ran a ==benchmark== test to compare query performance before and after the database optimization.
  - Our API response time is well below the industry ==benchmark== of 200ms.

## bottleneck
- phonetic: /ˈbɒtlnek/
- difficulty: 2
- categories: engineering, execution
- meaning: điểm nghẽn, nút thắt cổ chai làm chậm toàn hệ thống
- definition: a point in a process where the flow is restricted, causing delays or reduced performance
- usage:
  - **Danh từ**: a ==bottleneck== in the process / pipeline / system
  - Động từ: *identify / find / remove / fix* a ==bottleneck==
  - Kết hợp: *performance* ==bottleneck==, *database* ==bottleneck==
  - Cũng dùng làm động từ: "This slow query is ==bottlenecking== the whole service."
- example:
  - Profiling revealed that the N+1 database query was the main ==bottleneck== slowing down the dashboard.
  - The code review process has become a ==bottleneck==—PRs are waiting more than 3 days for feedback.

## brainstorm
- phonetic: /ˈbreɪnstɔːm/
- difficulty: 1
- categories: meetings, collaboration
- meaning: động não, cùng đưa ra ý tưởng tự do
- definition: to generate ideas freely in a group session without initial criticism
- usage:
  - **V + (about/on)**: ==brainstorm== ideas / solutions / approaches
  - **Danh từ**: hold a ==brainstorm==, in a ==brainstorm== session
  - **V2/V3**: *brainstormed* / *brainstormed*
  - Kết hợp: ==brainstorm== with the team, *quick* ==brainstorm==
- example:
  - Let's ==brainstorm== some approaches to reducing cold-start latency before the next architecture meeting.
  - The product and engineering teams held a ==brainstorm== session to define the MVP feature set.

## brief
- phonetic: /briːf/
- difficulty: 1
- categories: communication, collaboration
- meaning: thông báo, tóm tắt tình hình (cho ai); ngắn gọn
- definition: (v) to give someone essential information about a topic before they act; (adj) short in duration
- usage:
  - **Động từ — V + O**: ==brief== the team / manager / stakeholders *on* something
  - **V2/V3**: *briefed* / *briefed*
  - **Tính từ**: be ==brief==, keep it ==brief==
  - Danh từ: *a* ==brief== — "send a ==brief==", "project ==brief=="
- example:
  - Can you ==brief== the new engineers on the deployment process before they push to staging?
  - The PM sent a project ==brief== outlining the goals, timeline, and success metrics.

## capacity
- phonetic: /kəˈpæsɪti/
- difficulty: 2
- categories: planning, execution
- meaning: năng lực, công suất, khả năng tiếp nhận
- definition: the maximum amount a team or system can handle; available bandwidth to take on work
- usage:
  - **Danh từ không đếm được** (thường): team ==capacity==, system ==capacity==
  - Giới từ: *at full* ==capacity==, *beyond* ==capacity==, *within* ==capacity==
  - Kết hợp: ==capacity== planning, *engineering* ==capacity==, *server* ==capacity==
- example:
  - The team is currently at full ==capacity==—adding a new project now would impact existing deliverables.
  - We need to scale up server ==capacity== before the Black Friday traffic spike.

## clarify
- phonetic: /ˈklærɪfaɪ/
- difficulty: 1
- categories: communication, collaboration
- meaning: làm rõ, giải thích rõ ràng hơn
- definition: to make something easier to understand by explaining it in more detail
- usage:
  - **V + O**: ==clarify== a requirement / point / decision / expectation
  - **V + wh-clause**: "Can you ==clarify== what the acceptance criteria are?"
  - **V2/V3**: *clarified* / *clarified*
  - Kết hợp: *quickly / further* ==clarify==, need to ==clarify==
- example:
  - Before starting the implementation, please ==clarify== whether the API should support pagination.
  - The client's email was vague, so we scheduled a call to ==clarify== the requirements.

## collaborate
- phonetic: /kəˈlæbəreɪt/
- difficulty: 2
- categories: collaboration, communication
- meaning: cộng tác, hợp tác cùng nhau
- definition: to work jointly with others toward a shared goal
- usage:
  - **Nội động từ**: ==collaborate== + *with* someone + *on* something
  - **V2/V3**: *collaborated* / *collaborated*
  - Danh từ: *collaboration* — "cross-team ==collaboration=="
  - Kết hợp: *closely / effectively* ==collaborate==
- example:
  - The frontend and backend teams need to ==collaborate== closely on the API contract before parallel development begins.
  - We ==collaborated== with the data science team to integrate the recommendation engine into the app.

## commitment
- phonetic: /kəˈmɪtmənt/
- difficulty: 2
- categories: execution, planning
- meaning: cam kết, lời hứa thực hiện
- definition: a promise or obligation to do something, or a dedication to a goal
- usage:
  - **Danh từ**: make a ==commitment==, honor a ==commitment==, break a ==commitment==
  - Giới từ: ==commitment== *to* something ("==commitment== to quality")
  - Kết hợp: *sprint* ==commitment==, *long-term* ==commitment==, *team* ==commitment==
- example:
  - The sprint ==commitment== includes three user stories; please avoid adding scope mid-sprint.
  - Our ==commitment== to zero downtime deployments means every release goes through automated testing.

## comprehensive
- phonetic: /ˌkɒmprɪˈhensɪv/
- difficulty: 2
- categories: analysis, planning
- meaning: toàn diện, đầy đủ, bao quát
- definition: including all or nearly all aspects of something; thorough
- usage:
  - **Tính từ** trước danh từ: a ==comprehensive== review / plan / test suite / document
  - Phó từ: *comprehensively* review
  - Trái nghĩa: *partial*, *superficial*, *narrow*
- example:
  - We need a ==comprehensive== regression test suite before migrating to the new database schema.
  - The technical lead wrote a ==comprehensive== runbook covering every deployment scenario.

## consensus
- phonetic: /kənˈsensəs/
- difficulty: 2
- categories: communication, collaboration
- meaning: sự đồng thuận, nhất trí chung
- definition: a general agreement among all members of a group
- usage:
  - **Danh từ không đếm được**: reach / build / achieve ==consensus==
  - Giới từ: ==consensus== *on* a decision / approach
  - Kết hợp: *reach a* ==consensus==, *by* ==consensus==, *group* ==consensus==
- example:
  - After a long discussion, the architecture committee reached a ==consensus== on using PostgreSQL over MongoDB.
  - We try to make major technical decisions by ==consensus== rather than top-down mandate.

## convene
- phonetic: /kənˈviːn/
- difficulty: 2
- categories: meetings, collaboration
- meaning: triệu tập, tổ chức (cuộc họp, nhóm)
- definition: to bring people together for a meeting or formal gathering
- usage:
  - **V + O** (ngoại): ==convene== a meeting / session / committee
  - **V** (nội): The team ==convenes== every Monday.
  - **V2/V3**: *convened* / *convened*
  - Kết hợp: ==convene== *an emergency* meeting, ==convene== *virtually*
- example:
  - The engineering manager ==convened== an emergency meeting after the production outage was detected.
  - We ==convene== bi-weekly to review the product roadmap and reprioritize the backlog.

## coordinate
- phonetic: /kəʊˈɔːdɪneɪt/
- difficulty: 2
- categories: collaboration, communication
- meaning: phối hợp, điều phối giữa các bên
- definition: to organize people or efforts so they work together effectively
- usage:
  - **V + O**: ==coordinate== efforts / releases / schedules
  - **V + with**: ==coordinate== *with* another team / vendor / department
  - **V2/V3**: *coordinated* / *coordinated*
  - Danh từ: *coordination* — "cross-team ==coordination=="
- example:
  - You'll need to ==coordinate== with the DevOps team to schedule the maintenance window.
  - Poor ==coordination== between frontend and backend caused the API contract to be misaligned.

## criteria
- phonetic: /kraɪˈtɪəriə/
- difficulty: 2
- categories: analysis, planning
- meaning: tiêu chí (số nhiều của criterion)
- definition: the plural of criterion; standards or conditions used to judge or decide something
- usage:
  - ==Criteria== là **số nhiều**; số ít là *criterion*
  - Kết hợp: *acceptance* ==criteria==, *evaluation* ==criteria==, *success* ==criteria==
  - Cấu trúc: meet / satisfy / define the ==criteria==
  - Lỗi phổ biến: ~~"a criteria"~~ → đúng là "a **criterion**"
- example:
  - All tickets must have clearly defined ==acceptance criteria== before they are pulled into the sprint.
  - The vendor was selected based on three ==criteria==: cost, reliability, and SLA guarantees.

## critical
- phonetic: /ˈkrɪtɪkl/
- difficulty: 1
- categories: execution, planning
- meaning: quan trọng, then chốt; nghiêm trọng
- definition: extremely important; or indicating a serious problem requiring immediate attention
- usage:
  - **Tính từ**: a ==critical== issue / path / system / bug
  - Giới từ: ==critical== *to* success ("Testing is ==critical== *to* a stable release.")
  - Kết hợp: *mission-* ==critical==, ==critical== path, ==critical== bug, ==critical== dependency
- example:
  - The authentication service is ==critical== to all downstream features—do not deploy without full testing.
  - There is a ==critical== bug in the payment flow that is causing transaction failures for 5% of users.

## deadline
- phonetic: /ˈdedlaɪn/
- difficulty: 1
- categories: planning, execution
- meaning: thời hạn cuối, deadline
- definition: the latest time or date by which something must be completed
- usage:
  - **Danh từ**: meet / miss / extend / set a ==deadline==
  - Giới từ: *before* the ==deadline==, *by* the ==deadline==
  - Kết hợp: *hard* ==deadline==, *soft* ==deadline==, ==deadline== *pressure*
- example:
  - The feature must be code-complete by Friday—that is a ==hard deadline== tied to the marketing launch.
  - We missed the ==deadline== because three dependencies were blocked waiting for the security review.

## debug
- phonetic: /diːˈbʌɡ/
- difficulty: 1
- categories: engineering, execution
- meaning: gỡ lỗi, tìm và sửa lỗi trong code
- definition: to identify and remove errors or bugs from software code
- usage:
  - **V + O**: ==debug== the code / service / issue
  - **V2/V3**: *debugged* / *debugged*
  - Kết hợp: ==debug== *locally*, ==debug== *in production*, *hard to* ==debug==
  - Danh từ liên quan: *debugger*, *debugging session*
- example:
  - I spent three hours trying to ==debug== the race condition that only appeared under high concurrency.
  - Use the built-in ==debugger== to ==debug== the Lambda function locally before deploying.

## delegate
- phonetic: /ˈdelɪɡeɪt/
- difficulty: 2
- categories: execution, planning
- meaning: ủy quyền, giao phó (công việc hoặc quyền hạn) cho người khác
- definition: to assign responsibility or authority to someone else
- usage:
  - **V + O + to**: ==delegate== a task / responsibility / decision *to* someone
  - **V2/V3**: *delegated* / *delegated*
  - Danh từ: *delegation* — effective ==delegation==
  - Kết hợp: ==delegate== *effectively*, ==delegate== authority, refuse to ==delegate==
- example:
  - A good engineering manager knows how to ==delegate== technical decisions to senior engineers.
  - The tech lead ==delegated== the API design to the most experienced backend developer on the team.

## deliverable
- phonetic: /dɪˈlɪvərəbl/
- difficulty: 2
- categories: execution, planning
- meaning: sản phẩm bàn giao, kết quả cụ thể cần giao nộp
- definition: a specific output or result that must be produced and handed over as part of a project
- usage:
  - **Danh từ đếm được**: a ==deliverable==, the ==deliverables==
  - Kết hợp: *project* ==deliverables==, *key* ==deliverables==, define / list / track ==deliverables==
  - Giới từ: ==deliverable== *for* a project / sprint / client
- example:
  - The main ==deliverables== for Q3 are the new reporting dashboard and the SSO integration.
  - Each sprint should end with at least one shippable ==deliverable== that provides value to users.

## dependency
- phonetic: /dɪˈpendənsi/
- difficulty: 2
- categories: execution, planning
- meaning: sự phụ thuộc, thành phần hoặc bên phụ thuộc vào nhau
- definition: something that relies on or must be completed before another thing can proceed; also a software library relied upon
- usage:
  - **Danh từ**: a ==dependency==, multiple ==dependencies==
  - Giới từ: ==dependency== *on* a service / team / library
  - Kết hợp: *block* / *unblock* a ==dependency==, *external* ==dependency==, manage ==dependencies==
- example:
  - The frontend team is blocked because the backend API is a ==dependency== that isn't ready yet.
  - Always audit your npm ==dependencies== for security vulnerabilities before releasing to production.

## deploy
- phonetic: /dɪˈplɔɪ/
- difficulty: 2
- categories: engineering, execution
- meaning: triển khai (phần mềm lên môi trường)
- definition: to release and make software available in a live or staging environment
- usage:
  - **V + O + to**: ==deploy== the app / service / fix *to* staging / production
  - **V2/V3**: *deployed* / *deployed*
  - Danh từ: *deployment* — a ==deployment== pipeline, a ==deployment== window
  - Kết hợp: ==deploy== *automatically*, *zero-downtime* ==deploy==, rollback a ==deployment==
- example:
  - We ==deploy== to production every Friday after a full regression test passes in CI.
  - The ==deployment== failed because an environment variable was missing in the production config.

## document
- phonetic: /ˈdɒkjʊment/
- difficulty: 1
- categories: execution, planning
- meaning: ghi chép, tài liệu hóa
- definition: (v) to record information clearly so others can reference it later
- usage:
  - **V + O**: ==document== the process / API / decision / code
  - **V2/V3**: *documented* / *documented*
  - Danh từ: *documentation* — write ==documentation==, keep ==documentation== up to date
  - Kết hợp: *well-* ==documented==, *poorly* ==documented==, ==document== as you go
- example:
  - Every public API endpoint must be ==documented== in the OpenAPI spec before merging.
  - Please ==document== the architectural decision in the ADR so future engineers understand the trade-offs.

## draft
- phonetic: /drɑːft/
- difficulty: 1
- categories: execution, planning
- meaning: bản nháp; soạn thảo (văn bản, kế hoạch)
- definition: (n) a preliminary version of a document; (v) to write a first version
- usage:
  - **Danh từ**: *a first / rough* ==draft==, review a ==draft==, in ==draft== mode
  - **Động từ — V + O**: ==draft== a proposal / RFC / email / spec
  - **V2/V3**: *drafted* / *drafted*
  - Kết hợp: ==draft== *a response*, ==draft== *an RFC*, circulate a ==draft==
- example:
  - I'll ==draft== the technical specification by EOD tomorrow and share it for team review.
  - The ==draft== RFC for the new microservices architecture is in the shared Confluence page—please leave comments.

## effective
- phonetic: /ɪˈfektɪv/
- difficulty: 1
- categories: execution, planning
- meaning: hiệu quả (đạt được mục tiêu đề ra)
- definition: producing the intended or expected result; successful in achieving a goal
- usage:
  - **Tính từ**: an ==effective== solution / meeting / strategy / leader
  - Phân biệt với *efficient*: ==effective== = đúng việc cần làm; *efficient* = làm nhanh/ít tốn kém
  - Phó từ: *effectively* — "communicate *effectively*"
- example:
  - The new code review checklist has been ==effective== in reducing the number of bugs reaching production.
  - A daily stand-up is only ==effective== if everyone comes prepared with their blockers.

## efficient
- phonetic: /ɪˈfɪʃnt/
- difficulty: 1
- categories: execution, planning
- meaning: hiệu quả (tiết kiệm nguồn lực, thời gian, chi phí)
- definition: achieving results with minimum wasted time, effort, or resources
- usage:
  - **Tính từ**: an ==efficient== algorithm / process / developer
  - Phân biệt với *effective*: ==efficient== = làm nhanh/ít tốn; *effective* = đạt đúng mục tiêu
  - Phó từ: *efficiently* — "process requests *efficiently*"
- example:
  - The new caching layer made the search feature 10x more ==efficient== by reducing database round trips.
  - We reorganized the sprint ceremonies to be more ==efficient==—stand-ups are now capped at 15 minutes.

## escalate
- phonetic: /ˈeskəleɪt/
- difficulty: 2
- categories: execution, planning
- meaning: leo thang; báo cáo lên cấp trên; nâng cao mức độ ưu tiên
- definition: to increase in severity or urgency; to refer an issue to someone with more authority
- usage:
  - **V + O + to**: ==escalate== an issue / ticket / concern *to* management / the CTO
  - **V** (nội, khi vấn đề tự leo thang): "The outage ==escalated== quickly."
  - **V2/V3**: *escalated* / *escalated*
  - Kết hợp: ==escalate== *immediately*, need to ==escalate==, *when to* ==escalate==
- example:
  - If you are blocked for more than a day, please ==escalate== the issue to your engineering manager.
  - The P1 incident ==escalated== to the VP of Engineering within the first hour of the outage.

## estimate
- phonetic: /ˈestɪmeɪt/
- difficulty: 1
- categories: planning, execution
- meaning: ước tính, dự đoán (thời gian, chi phí, độ phức tạp)
- definition: (v) to approximately calculate the time, cost, or size of something; (n) the resulting figure
- usage:
  - **V + O**: ==estimate== the effort / time / complexity / cost
  - **Danh từ**: give / provide an ==estimate==, rough ==estimate==
  - Kết hợp: *story point* ==estimate==, *time* ==estimate==, ==estimate== *in days*
  - Lưu ý phát âm: danh từ /ˈestɪmət/, động từ /ˈestɪmeɪt/
- example:
  - Please ==estimate== the implementation effort in story points during the backlog refinement session.
  - My ==estimate== for the API integration is five days, but that assumes the third-party docs are accurate.

## evaluate
- phonetic: /ɪˈvæljueɪt/
- difficulty: 2
- categories: analysis, planning
- meaning: đánh giá, thẩm định một cách có hệ thống
- definition: to assess something carefully before making a judgment or decision
- usage:
  - **V + O**: ==evaluate== a solution / vendor / candidate / option
  - **V2/V3**: *evaluated* / *evaluated*
  - Danh từ: *evaluation* — run an ==evaluation==, evaluation ==criteria==
  - Kết hợp: ==evaluate== *thoroughly*, ==evaluate== trade-offs
- example:
  - We ==evaluated== three message queue solutions—Kafka, RabbitMQ, and SQS—before choosing Kafka.
  - The hiring panel will ==evaluate== each candidate against a consistent set of technical ==criteria==.

## execute
- phonetic: /ˈeksɪkjuːt/
- difficulty: 2
- categories: execution, planning
- meaning: thực thi, triển khai (kế hoạch, chiến lược)
- definition: to carry out or implement a plan, task, or strategy
- usage:
  - **V + O**: ==execute== a plan / strategy / query / script
  - **V2/V3**: *executed* / *executed*
  - Danh từ: *execution* — flawless ==execution==, ==execution== plan
  - Kết hợp: *flawlessly* ==execute==, ==execute== *against* a plan
- example:
  - The team ==executed== the migration plan without any data loss or downtime.
  - Having a brilliant strategy is worthless if you can't ==execute== it effectively.

## expedite
- phonetic: /ˈekspɪdaɪt/
- difficulty: 3
- categories: execution, planning
- meaning: thúc đẩy, đẩy nhanh tiến độ xử lý
- definition: to make something happen more quickly than it normally would
- usage:
  - **V + O**: ==expedite== a request / review / process / ticket
  - **V2/V3**: *expedited* / *expedited*
  - Kết hợp: ==expedite== *the approval*, ==expedite== *the delivery*, request to ==expedite==
- example:
  - Could you ==expedite== the security review? We need to release before the compliance audit next week.
  - The client requested we ==expedite== the onboarding process for their enterprise account.

## facilitate
- phonetic: /fəˈsɪlɪteɪt/
- difficulty: 2
- categories: execution, planning
- meaning: tạo điều kiện, điều phối (cuộc họp, quy trình)
- definition: to make a process or meeting easier by organizing and guiding it without being the decision-maker
- usage:
  - **V + O**: ==facilitate== a meeting / workshop / discussion / process
  - **V2/V3**: *facilitated* / *facilitated*
  - Danh từ: *facilitator* — the ==facilitator== of the retrospective
  - Kết hợp: *effectively* ==facilitate==, ==facilitate== a *retrospective / sprint planning*
- example:
  - The Scrum Master's role is to ==facilitate== the sprint ceremonies, not to manage the engineers.
  - She ==facilitated== a design sprint to help the team align on the new user onboarding flow.

## feasibility
- phonetic: /ˌfiːzəˈbɪlɪti/
- difficulty: 3
- categories: analysis, planning
- meaning: tính khả thi
- definition: the degree to which something is possible or practical given the constraints
- usage:
  - **Danh từ không đếm được**: assess / determine / question the ==feasibility==
  - Kết hợp: ==feasibility== *study / analysis / report*, *technical* ==feasibility==
  - Tính từ gốc: *feasible* — "Is this ==feasible== within the timeline?"
- example:
  - Before committing to the feature, the tech lead ran a ==feasibility== study to assess the technical risks.
  - The CTO questioned the ==feasibility== of rebuilding the entire platform in six months.

## feedback
- phonetic: /ˈfiːdbæk/
- difficulty: 1
- categories: communication, collaboration
- meaning: phản hồi, góp ý
- definition: information given in response to work, behavior, or a process, used to improve it
- usage:
  - **Danh từ không đếm được**: give / receive / provide ==feedback==
  - Giới từ: ==feedback== *on* something ("==feedback== *on* the PR")
  - Kết hợp: *constructive* ==feedback==, *actionable* ==feedback==, ==feedback== loop
  - Sai phổ biến: ~~"a feedback"~~ → ==feedback== không có mạo từ *a*
- example:
  - Please leave ==constructive feedback== on the pull request within 24 hours.
  - The retrospective is a safe space to share ==feedback== on the team's processes and dynamics.

## flexible
- phonetic: /ˈfleksɪbl/
- difficulty: 1
- categories: collaboration, communication
- meaning: linh hoạt, dễ thích nghi với thay đổi
- definition: able to change or be changed easily in response to different circumstances
- usage:
  - **Tính từ**: a ==flexible== schedule / approach / architecture / team
  - Phó từ: *flexibly* — "work *flexibly*"
  - Danh từ: *flexibility* — build in ==flexibility==, allow for ==flexibility==
  - Kết hợp: ==flexible== *working hours*, ==flexible== *release cadence*
- example:
  - We keep our sprint goals ==flexible== enough to accommodate urgent P1 bugs without derailing the team.
  - A ==flexible== microservices architecture allows us to scale individual components independently.

## follow up
- phonetic: /ˈfɒləʊ ʌp/
- difficulty: 1
- categories: meetings, collaboration
- meaning: theo dõi tiếp theo, nhắc nhở, làm việc tiếp theo sau đó
- definition: to take further action on something previously discussed or started
- usage:
  - **Cụm động từ — V + up (+ with/on)**: ==follow up== *with* someone, ==follow up== *on* an issue
  - **Danh từ ghép**: a ==follow-up== email / meeting / action item
  - **V2/V3**: *followed up* / *followed up*
  - Kết hợp: I'll ==follow up== by EOD, can you ==follow up== with the vendor?
- example:
  - I'll ==follow up== with the client after the demo to gather their initial feedback.
  - There are three ==follow-up== action items from today's meeting—they've been logged in Jira.

## framework
- phonetic: /ˈfreɪmwɜːk/
- difficulty: 2
- categories: engineering, execution
- meaning: khung, nền tảng (kỹ thuật hoặc quy trình)
- definition: a structured system or set of guidelines used as a foundation for development or decision-making
- usage:
  - **Danh từ**: use a ==framework==, build on a ==framework==
  - Kết hợp: *software* ==framework==, *architectural* ==framework==, *Agile* ==framework==
  - Phổ biến trong tech: React ==framework==, Spring ==framework==, testing ==framework==
- example:
  - We chose Vue.js as our frontend ==framework== because of its gentle learning curve and strong ecosystem.
  - The team follows an ==Agile framework== with two-week sprints and weekly demos to stakeholders.

## impact
- phonetic: /ˈɪmpækt/
- difficulty: 1
- categories: analysis, planning
- meaning: tác động, ảnh hưởng
- definition: the effect or influence that something has on a person, system, or process
- usage:
  - **Danh từ**: have / assess / minimize / measure ==impact==
  - **Động từ**: ==impact== a system / team / user ("This change will ==impact== all users.")
  - Giới từ: ==impact== *on* — "the ==impact== *on* performance"
  - Kết hợp: *high / low / business* ==impact==, ==impact== analysis
- example:
  - Before merging, always do an ==impact== analysis to understand which services will be affected.
  - The new caching strategy had a significant ==impact== on reducing server load during peak hours.

## implement
- phonetic: /ˈɪmplɪment/
- difficulty: 2
- categories: engineering, execution
- meaning: triển khai, thực hiện (tính năng, giải pháp)
- definition: to put a plan, decision, or system into effect
- usage:
  - **V + O**: ==implement== a feature / solution / change / policy
  - **V2/V3**: *implemented* / *implemented*
  - Danh từ: *implementation* — the ==implementation== plan, full ==implementation==
  - Kết hợp: ==implement== *from scratch*, *fully / partially* ==implement==
- example:
  - The team will ==implement== the OAuth2 flow in this sprint and ship it to staging by Thursday.
  - The ==implementation== took longer than estimated because the third-party SDK had undocumented limitations.

## initiative
- phonetic: /ɪˈnɪʃɪətɪv/
- difficulty: 2
- categories: planning, execution
- meaning: sáng kiến, hành động chủ động; dự án/chương trình chiến lược
- definition: a new plan or action intended to solve a problem or improve something; the ability to act independently
- usage:
  - **Danh từ đếm được**: launch / drive / lead an ==initiative==
  - **Không đếm được** (tính cách): show / take ==initiative==
  - Kết hợp: *strategic* ==initiative==, *company-wide* ==initiative==, take the ==initiative==
- example:
  - The DevOps ==initiative== reduced deployment time from 2 hours to 15 minutes within one quarter.
  - Engineers who take ==initiative== and identify improvements without being asked are highly valued here.

## insight
- phonetic: /ˈɪnsaɪt/
- difficulty: 2
- categories: analysis, planning
- meaning: thấu hiểu sâu sắc, nhận thức có giá trị
- definition: a deep understanding of a situation, often revealing something not immediately obvious
- usage:
  - **Danh từ**: gain / provide / share an ==insight==
  - **Đếm được**: *an* ==insight==, *key* ==insights==
  - Giới từ: ==insight== *into* something ("==insight== *into* user behavior")
  - Kết hợp: *data-driven* ==insights==, *business* ==insights==, actionable ==insights==
- example:
  - The A/B test gave us valuable ==insights== into how users interact with the new onboarding flow.
  - The analytics dashboard was built to surface ==insights== that help the product team make better decisions.

## integrate
- phonetic: /ˈɪntɪɡreɪt/
- difficulty: 2
- categories: engineering, execution
- meaning: tích hợp, kết hợp các hệ thống hoặc thành phần lại với nhau
- definition: to combine separate systems, parts, or services so they work together as a whole
- usage:
  - **V + O + with / into**: ==integrate== a service *with* / *into* the platform
  - **V2/V3**: *integrated* / *integrated*
  - Danh từ: *integration* — third-party ==integration==, ==integration== testing
  - Kết hợp: *seamlessly* ==integrate==, ==integrate== *via API*, continuous ==integration==
- example:
  - We need to ==integrate== the payment gateway with our checkout service before the launch.
  - The CI pipeline automatically runs ==integration== tests every time a PR is merged to the main branch.

## iterate
- phonetic: /ˈɪtəreɪt/
- difficulty: 2
- categories: execution, planning
- meaning: lặp lại và cải tiến, làm nhiều vòng
- definition: to repeat a process with improvements based on feedback, particularly in software development
- usage:
  - **Nội / ngoại động từ**: ==iterate== *on* a design / feature / prototype
  - **V2/V3**: *iterated* / *iterated*
  - Danh từ: *iteration* — the next ==iteration==, rapid ==iteration==
  - Kết hợp: ==iterate== *quickly*, ==iterate== *based on feedback*
- example:
  - We shipped an MVP and plan to ==iterate== on it based on real user feedback over the next two sprints.
  - The design team went through five ==iterations== before settling on the final dashboard layout.

## launch
- phonetic: /lɔːntʃ/
- difficulty: 1
- categories: execution, planning
- meaning: ra mắt, phát hành (sản phẩm, tính năng)
- definition: to officially release a product, feature, or service for public or internal use
- usage:
  - **V + O**: ==launch== a product / feature / campaign / service
  - **Danh từ**: a product ==launch==, ==launch== day, ==launch== plan
  - **V2/V3**: *launched* / *launched*
  - Kết hợp: soft ==launch==, hard ==launch==, ==launch== *to production*
- example:
  - We plan to ==launch== the new mobile app to all users in Q4 after the beta testing phase.
  - The ==launch== checklist includes smoke tests, monitoring alerts, and a rollback plan.

## legacy
- phonetic: /ˈleɡəsi/
- difficulty: 2
- categories: engineering, execution
- meaning: hệ thống cũ, di sản (code/hạ tầng không còn hiện đại)
- definition: old or outdated code, systems, or infrastructure that is still in use but difficult to maintain
- usage:
  - **Tính từ** trước danh từ: ==legacy== code / system / database / API
  - **Danh từ**: deal with ==legacy==, migrate away from ==legacy==
  - Kết hợp: ==legacy== *codebase*, ==legacy== *infrastructure*, maintain ==legacy== systems
- example:
  - The team spends 40% of each sprint dealing with ==legacy== code that lacks documentation and tests.
  - Our goal is to gradually replace the ==legacy== monolith with independently deployable microservices.

## leverage
- phonetic: /ˈlevərɪdʒ/
- difficulty: 3
- categories: execution, planning
- meaning: tận dụng, khai thác tối đa (nguồn lực, công cụ, lợi thế)
- definition: to use something to its maximum advantage
- usage:
  - **V + O**: ==leverage== existing tools / infrastructure / expertise / data
  - **V2/V3**: *leveraged* / *leveraged*
  - Danh từ: *leverage* (không đếm được) — have ==leverage== in a negotiation
  - Kết hợp: ==leverage== *cloud services*, ==leverage== *open-source*
- example:
  - Instead of building from scratch, we ==leveraged== AWS managed services to reduce operational overhead.
  - We can ==leverage== the existing authentication module rather than implementing OAuth again.

## metrics
- phonetic: /ˈmetrɪks/
- difficulty: 2
- categories: analysis, planning
- meaning: số liệu đo lường, chỉ số đánh giá
- definition: quantitative measures used to track performance, progress, or quality
- usage:
  - Thường dùng số nhiều: ==metrics==; số ít ít phổ biến hơn: *a metric*
  - Kết hợp: *define / track / monitor / report* ==metrics==
  - Phổ biến: *key* ==metrics==, *performance* ==metrics==, *business* ==metrics==, *KPI* (Key Performance Indicator)
- example:
  - The team tracks three key ==metrics==: deployment frequency, lead time, and mean time to recovery.
  - We need to define success ==metrics== before we start building, not after we ship.

## milestone
- phonetic: /ˈmaɪlstəʊn/
- difficulty: 2
- categories: planning, execution
- meaning: cột mốc quan trọng trong dự án
- definition: a significant point or event in the progress of a project, used to mark achievements
- usage:
  - **Danh từ**: reach / hit / define a ==milestone==
  - Kết hợp: *project* ==milestone==, ==milestone== *review*, *key* ==milestones==
  - Giới từ: *by* the ==milestone== date, *at* each ==milestone==
- example:
  - The first ==milestone== is the working prototype; the second is the beta release to internal users.
  - We celebrate every ==milestone== as a team—it's important to acknowledge progress, not just the final delivery.

## mitigate
- phonetic: /ˈmɪtɪɡeɪt/
- difficulty: 3
- categories: execution, planning
- meaning: giảm thiểu, hạn chế (rủi ro, tác động tiêu cực)
- definition: to reduce the severity, seriousness, or painfulness of something
- usage:
  - **V + O**: ==mitigate== risk / impact / damage / downtime
  - **V2/V3**: *mitigated* / *mitigated*
  - Danh từ: *mitigation* — risk ==mitigation== plan, ==mitigation== strategy
  - Kết hợp: ==mitigate== *the risk of*, ==mitigate== *potential issues*
- example:
  - Feature flags allow us to ==mitigate== risk by rolling out changes to 1% of users first.
  - The disaster recovery plan is designed to ==mitigate== the impact of a full region outage.

## monitor
- phonetic: /ˈmɒnɪtər/
- difficulty: 1
- categories: execution, planning
- meaning: theo dõi, giám sát liên tục
- definition: to regularly check and observe a system, process, or metric over time
- usage:
  - **V + O**: ==monitor== performance / logs / uptime / errors
  - **V2/V3**: *monitored* / *monitored*
  - Danh từ: *monitoring* — set up ==monitoring==, ==monitoring== dashboard, *real-time* ==monitoring==
  - Kết hợp: *actively / closely* ==monitor==, ==monitor== *in real time*
- example:
  - We use Datadog to ==monitor== API latency and error rates across all microservices 24/7.
  - After every production deployment, the on-call engineer must ==monitor== the dashboards for 30 minutes.

## negotiate
- phonetic: /nɪˈɡəʊʃieɪt/
- difficulty: 2
- categories: communication, collaboration
- meaning: thương lượng, đàm phán để đi đến thỏa thuận
- definition: to discuss and reach an agreement through compromise
- usage:
  - **V + O / V + with**: ==negotiate== a contract / timeline / scope *with* a client / vendor
  - **V2/V3**: *negotiated* / *negotiated*
  - Danh từ: *negotiation* — enter ==negotiations==, in ==negotiation== with
  - Kết hợp: ==negotiate== *the scope*, ==negotiate== *a deadline extension*
- example:
  - The PM ==negotiated== a two-week extension with the client after the requirements changed significantly.
  - When the vendor's quote exceeded the budget, we ==negotiated== a reduced scope for phase one.

## objective
- phonetic: /əbˈdʒektɪv/
- difficulty: 2
- categories: planning, execution
- meaning: mục tiêu (cụ thể, có thể đo lường); khách quan
- definition: (n) a specific, measurable goal; (adj) based on facts rather than personal feelings
- usage:
  - **Danh từ**: set / define / achieve an ==objective==
  - Kết hợp: *business / strategic* ==objectives==, *OKR* (Objectives and Key Results)
  - **Tính từ**: stay ==objective==, an ==objective== assessment
  - Phân biệt: *goal* (chung chung) vs *==objective==* (cụ thể, đo được)
- example:
  - Our Q3 ==objective== is to reduce the P95 API latency from 800ms to under 200ms.
  - Code review feedback should be ==objective== and focus on the code, not the author.

## onboard
- phonetic: /ˈɒnbɔːd/
- difficulty: 2
- categories: collaboration, communication
- meaning: tiếp nhận và hướng dẫn người mới (nhân viên hoặc khách hàng)
- definition: to integrate a new employee or client into a system or organization
- usage:
  - **V + O**: ==onboard== a new hire / client / customer
  - **V2/V3**: *onboarded* / *onboarded*
  - Danh từ: *onboarding* — the ==onboarding== process, ==onboarding== documentation
  - Kết hợp: ==onboard== *quickly*, ==onboard== *remotely*, smooth ==onboarding==
- example:
  - We use a 30-60-90 day plan to ==onboard== new engineers effectively and set clear expectations.
  - Good ==onboarding== documentation reduces the time it takes a new hire to make their first contribution.

## optimize
- phonetic: /ˈɒptɪmaɪz/
- difficulty: 2
- categories: engineering, execution
- meaning: tối ưu hóa, cải thiện để đạt hiệu suất tốt nhất
- definition: to make something as effective, efficient, or functional as possible
- usage:
  - **V + O**: ==optimize== performance / queries / code / memory / the pipeline
  - **V + for**: ==optimize== *for* speed / cost / readability
  - **V2/V3**: *optimized* / *optimized*
  - Danh từ: *optimization* — query ==optimization==, performance ==optimization==
- example:
  - We ==optimized== the database queries and reduced the average page load time by 60%.
  - Before ==optimizing== for performance, always measure first—don't guess where the bottleneck is.

## outcome
- phonetic: /ˈaʊtkʌm/
- difficulty: 1
- categories: analysis, planning
- meaning: kết quả, đầu ra cuối cùng
- definition: the final result or consequence of a process, meeting, or action
- usage:
  - **Danh từ**: achieve / measure / define the ==outcome==
  - Kết hợp: *desired* ==outcome==, *business* ==outcome==, *expected* ==outcome==
  - Phân biệt: *output* (thứ bạn tạo ra) vs *==outcome==* (giá trị hoặc thay đổi thực tế)
- example:
  - The ==outcome== of the sprint review was a decision to pivot the feature based on user testing feedback.
  - We focus on business ==outcomes==, not just feature delivery—shipping code is not the same as creating value.

## overview
- phonetic: /ˈəʊvəvjuː/
- difficulty: 1
- categories: communication, collaboration
- meaning: cái nhìn tổng quan, tóm tắt ở cấp độ cao
- definition: a brief summary or general description of a subject
- usage:
  - **Danh từ**: give / provide an ==overview==
  - Kết hợp: *high-level* ==overview==, *quick* ==overview==, project ==overview==
  - Giới từ: ==overview== *of* something ("an ==overview== *of* the architecture")
- example:
  - Let me give you a quick ==overview== of the system architecture before we dive into the details.
  - The kickoff meeting should include an ==overview== of the project goals, timeline, and team responsibilities.

## performance
- phonetic: /pəˈfɔːməns/
- difficulty: 1
- categories: engineering, execution
- meaning: hiệu suất; kết quả thực hiện công việc
- definition: how well a system, process, or person functions relative to expectations or benchmarks
- usage:
  - **Danh từ không đếm được**: measure / improve / track ==performance==
  - Kết hợp: *system* ==performance==, ==performance== *review*, ==performance== *benchmark*
  - Tính từ: *high-==performance==*, *==performance==-critical*
- example:
  - The quarterly ==performance== review includes feedback from peers, direct reports, and the engineering manager.
  - ==Performance== profiling showed that 80% of the latency came from a single unindexed database query.

## phase
- phonetic: /feɪz/
- difficulty: 1
- categories: planning, execution
- meaning: giai đoạn trong dự án hoặc quy trình
- definition: a distinct stage in a process or project
- usage:
  - **Danh từ**: *in* ==phase== one, *enter / complete* a ==phase==
  - Kết hợp: ==phase== *one / two / three*, *discovery* ==phase==, *testing* ==phase==, *rollout* ==phase==
  - **Động từ**: ==phase== *in / out* — "==phase== out the legacy system"
- example:
  - ==Phase== one covers the core checkout flow; ==phase== two will add the loyalty points integration.
  - We are ==phasing== out the old REST API and ==phasing== in GraphQL over the next two quarters.

## prioritize
- phonetic: /praɪˈɒrɪtaɪz/
- difficulty: 2
- categories: planning, execution
- meaning: ưu tiên hóa, sắp xếp theo thứ tự quan trọng
- definition: to arrange tasks or items in order of importance or urgency
- usage:
  - **V + O**: ==prioritize== tasks / bugs / features / the backlog
  - **V2/V3**: *prioritized* / *prioritized*
  - Danh từ: *priority* / *prioritization* — ==prioritization== framework
  - Kết hợp: ==prioritize== *ruthlessly*, ==prioritize== *based on impact*
- example:
  - With limited engineering capacity, we must ==prioritize== features that deliver the highest business value.
  - The product manager is responsible for ==prioritizing== the backlog before each sprint planning session.

## proceed
- phonetic: /prəˈsiːd/
- difficulty: 1
- categories: execution, planning
- meaning: tiến hành, tiếp tục (với kế hoạch đã được xác nhận)
- definition: to continue doing something or begin after a pause or confirmation
- usage:
  - **Nội động từ**: ==proceed== *with* a plan / deployment / rollout
  - **V2/V3**: *proceeded* / *proceeded*
  - Kết hợp: ==proceed== *as planned*, ==proceed== *with caution*, *ready to* ==proceed==
- example:
  - Once the stakeholders approve the design, we will ==proceed== with implementation.
  - Do not ==proceed== with the production deployment until the rollback plan has been tested.

## productive
- phonetic: /prəˈdʌktɪv/
- difficulty: 1
- categories: execution, planning
- meaning: có năng suất, hiệu quả trong công việc
- definition: achieving a lot; generating useful results in a given amount of time
- usage:
  - **Tính từ**: a ==productive== meeting / day / team / session
  - Phó từ: *productively* — work *productively*
  - Danh từ: *productivity* — boost / track ==productivity==
  - Kết hợp: *highly* ==productive==, ==productive== *collaboration*
- example:
  - The team had a ==productive== sprint planning session—all stories were estimated and accepted in 90 minutes.
  - Limiting meetings to those with a clear ==agenda== keeps engineers ==productive== and in flow.

## progress
- phonetic: /ˈprəʊɡres/ (n) /prəˈɡres/ (v)
- difficulty: 1
- categories: execution, planning
- meaning: tiến độ, sự tiến triển; tiến lên
- definition: (n) forward movement toward a goal; (v) to move forward or improve
- usage:
  - **Danh từ**: make / track / report ==progress==
  - Giới từ: ==progress== *on* something ("==progress== *on* the migration")
  - **Động từ**: the project is ==progressing== well
  - Kết hợp: *in* ==progress==, *steady* ==progress==, ==progress== *update*
- example:
  - Please share a ==progress== update in the team channel at the end of each day this week.
  - The database migration is in ==progress==—40% of records have been moved without errors.

## propose
- phonetic: /prəˈpəʊz/
- difficulty: 1
- categories: communication, collaboration
- meaning: đề xuất, đưa ra ý kiến để thảo luận
- definition: to put forward an idea, plan, or suggestion for consideration
- usage:
  - **V + O**: ==propose== a solution / approach / change
  - **V + that-clause**: "I ==propose== that we move to a microservices architecture."
  - **V2/V3**: *proposed* / *proposed*
  - Danh từ: *proposal* — write / submit a ==proposal==
- example:
  - The backend lead ==proposed== replacing the polling mechanism with WebSockets to reduce server load.
  - I'd like to ==propose== a 20% time allocation for technical debt each sprint.

## prototype
- phonetic: /ˈprəʊtətaɪp/
- difficulty: 2
- categories: execution, planning
- meaning: nguyên mẫu, phiên bản thử nghiệm ban đầu
- definition: an early working model of a product used to test concepts before full development
- usage:
  - **Danh từ**: build / create / test a ==prototype==
  - **Động từ**: ==prototype== a feature / solution
  - Kết hợp: *clickable* ==prototype==, *low-fidelity* ==prototype==, *proof-of-concept* (POC)
  - **V2/V3**: *prototyped* / *prototyped*
- example:
  - We built a ==clickable prototype== in Figma to validate the UX concept with users before writing any code.
  - The team ==prototyped== the AI search feature in a two-day spike to assess its technical feasibility.

## recommend
- phonetic: /ˌrekəˈmend/
- difficulty: 1
- categories: communication, collaboration
- meaning: đề nghị, khuyến nghị (dựa trên kinh nghiệm hoặc phân tích)
- definition: to suggest something as the best option based on knowledge or experience
- usage:
  - **V + O**: ==recommend== a tool / approach / candidate
  - **V + that-clause**: "I ==recommend== that we use Terraform for infrastructure as code."
  - **V2/V3**: *recommended* / *recommended*
  - Danh từ: *recommendation* — follow / make a ==recommendation==
- example:
  - I ==recommend== adding an integration test for this endpoint before merging—it's a critical path.
  - The security audit report ==recommended== rotating all API keys and enabling MFA across all accounts.

## refactor
- phonetic: /riːˈfæktər/
- difficulty: 2
- categories: engineering, execution
- meaning: tái cấu trúc mã nguồn mà không thay đổi hành vi bên ngoài
- definition: to restructure existing code to improve its readability, maintainability, or performance without changing its external behavior
- usage:
  - **V + O**: ==refactor== the code / module / service / function
  - **V2/V3**: *refactored* / *refactored*
  - Danh từ: *refactoring* — a ==refactoring== sprint, code ==refactoring==
  - Kết hợp: ==refactor== *safely*, ==refactor== *with test coverage*
- example:
  - We scheduled a ==refactoring== sprint to pay down the technical debt before adding new features.
  - Never ==refactor== code that doesn't have test coverage—you won't know if you've broken anything.

## release
- phonetic: /rɪˈliːs/
- difficulty: 1
- categories: engineering, execution
- meaning: phiên bản phát hành; phát hành (phần mềm)
- definition: (n) a version of software made available to users; (v) to make software available
- usage:
  - **Danh từ**: cut / plan / schedule a ==release==
  - **Động từ**: ==release== version 2.0 / the hotfix
  - Kết hợp: ==release== *notes*, ==release== *candidate (RC)*, ==release== *pipeline*
  - **V2/V3**: *released* / *released*
- example:
  - The ==release== notes must be written and approved before we tag the ==release== candidate.
  - We ==release== a new version every two weeks following our sprint cadence.

## requirement
- phonetic: /rɪˈkwaɪərmənt/
- difficulty: 1
- categories: planning, execution
- meaning: yêu cầu (tính năng, hệ thống, kinh doanh)
- definition: something that is needed or specified as a condition for a project or system
- usage:
  - **Danh từ đếm được**: a ==requirement==, the ==requirements==
  - Kết hợp: *business / functional / non-functional / technical* ==requirements==
  - Động từ: define / gather / document / meet ==requirements==
- example:
  - All ==requirements== must be reviewed and signed off by the product owner before development begins.
  - The non-functional ==requirements== include 99.9% uptime and a P95 response time under 300ms.

## resolve
- phonetic: /rɪˈzɒlv/
- difficulty: 2
- categories: execution, planning
- meaning: giải quyết, xử lý dứt điểm (vấn đề, xung đột, lỗi)
- definition: to find a solution to a problem or bring a conflict to an end
- usage:
  - **V + O**: ==resolve== an issue / bug / conflict / ticket
  - **V2/V3**: *resolved* / *resolved*
  - Danh từ: *resolution* — ==resolution== time, conflict ==resolution==
  - Kết hợp: *quickly / permanently* ==resolve==, ==resolve== *a merge conflict*
- example:
  - The P1 incident was ==resolved== within 45 minutes thanks to the team's runbook.
  - Please ==resolve== all merge conflicts locally before requesting a code review.

## resource
- phonetic: /rɪˈzɔːs/
- difficulty: 1
- categories: planning, execution
- meaning: nguồn lực (người, thời gian, ngân sách, hệ thống)
- definition: anything that can be used to achieve a goal, including people, tools, time, and budget
- usage:
  - **Danh từ**: allocate / manage / stretch ==resources==
  - Kết hợp: *human / cloud / financial* ==resources==, *limited* ==resources==, ==resource== planning
  - Động từ: ==resource== a project (ít phổ biến hơn trong kỹ thuật)
- example:
  - The project was delayed because we didn't have the ==resources== to tackle both initiatives simultaneously.
  - Cloud ==resources== are auto-scaled based on traffic to optimize cost and performance.

## review
- phonetic: /rɪˈvjuː/
- difficulty: 1
- categories: analysis, planning
- meaning: đánh giá, xem xét, kiểm tra
- definition: to examine or assess something carefully, often before a decision or release
- usage:
  - **V + O**: ==review== code / a PR / a design / a document
  - **Danh từ**: a code ==review==, a design ==review==, a ==review== cycle
  - **V2/V3**: *reviewed* / *reviewed*
  - Kết hợp: *peer* ==review==, *architecture* ==review==, ==review== *board*
- example:
  - Every PR must have at least two approvals before it can be merged to the main branch.
  - The quarterly ==review== covers delivery metrics, team health, and technical debt status.

## risk
- phonetic: /rɪsk/
- difficulty: 1
- categories: analysis, planning
- meaning: rủi ro, mối nguy cơ có thể xảy ra
- definition: the possibility that something could go wrong or cause harm to a project or system
- usage:
  - **Danh từ**: identify / assess / mitigate / accept a ==risk==
  - Kết hợp: *technical / security / business* ==risk==, ==risk== *register*, ==risk== *management*
  - **Động từ**: ==risk== losing data, ==risk== downtime
- example:
  - Always create a ==risk== register at the start of a project and review it at each milestone.
  - Deploying on a Friday is a ==risk== we try to avoid—if something breaks, the team has the whole weekend to fix it.

## roadmap
- phonetic: /ˈrəʊdmæp/
- difficulty: 1
- categories: planning, execution
- meaning: lộ trình, kế hoạch dài hạn của sản phẩm hoặc hệ thống
- definition: a high-level plan that outlines goals, priorities, and milestones over a future time period
- usage:
  - **Danh từ**: define / publish / review a ==roadmap==
  - Kết hợp: *product* ==roadmap==, *technical* ==roadmap==, *quarterly* ==roadmap==
  - Giới từ: *on the* ==roadmap==, *in the* ==roadmap==
- example:
  - The product ==roadmap== for next year prioritizes mobile improvements and third-party integrations.
  - Refactoring the authentication service has been on the technical ==roadmap== for two quarters.

## robust
- phonetic: /rəʊˈbʌst/
- difficulty: 3
- categories: analysis, planning
- meaning: mạnh mẽ, vững chắc, đáng tin cậy trong mọi tình huống
- definition: strong, reliable, and able to handle errors, edge cases, and high load without failing
- usage:
  - **Tính từ**: a ==robust== system / solution / architecture / test suite
  - Phó từ: *robustly* — handle errors *robustly*
  - Danh từ: *robustness* — ensure ==robustness==
  - Kết hợp: ==robust== *error handling*, ==robust== *infrastructure*
- example:
  - A ==robust== retry mechanism ensures the service recovers gracefully from transient network failures.
  - Building a ==robust== test suite now will save significant debugging time in the future.

## rollout
- phonetic: /ˈrəʊlaʊt/
- difficulty: 2
- categories: engineering, execution
- meaning: triển khai diện rộng, ra mắt dần từng bước
- definition: the process of gradually releasing a feature or system to users in stages
- usage:
  - **Danh từ**: plan / manage / oversee the ==rollout==
  - Kết hợp: *phased / gradual / global* ==rollout==, ==rollout== *plan*, canary ==rollout==
  - **Động từ ghép**: ==roll out== a feature (two words as a verb)
- example:
  - We will use a canary ==rollout==, exposing the new checkout flow to 5% of users before full launch.
  - The global ==rollout== is planned in three phases: APAC first, then EMEA, then North America.

## scalable
- phonetic: /ˈskeɪləbl/
- difficulty: 2
- categories: engineering, execution
- meaning: có khả năng mở rộng khi tải tăng
- definition: able to handle increased load or growth without significant rework or performance degradation
- usage:
  - **Tính từ**: a ==scalable== architecture / solution / system / design
  - Danh từ: *scalability* — ensure / improve ==scalability==
  - Kết hợp: *horizontally / vertically* ==scalable==, *highly* ==scalable==
- example:
  - The microservices architecture is ==scalable== because each service can be scaled independently.
  - Build ==scalable== solutions from the start—refactoring for scalability after launch is extremely costly.

## scope
- phonetic: /skəʊp/
- difficulty: 2
- categories: planning, execution
- meaning: phạm vi (của dự án, tính năng, hoặc sprint)
- definition: the defined boundaries of a project—what is and is not included
- usage:
  - **Danh từ**: define / limit / expand the ==scope==
  - Kết hợp: *project* ==scope==, ==scope== *creep* (phạm vi bị phình to), *in / out of* ==scope==
  - **Động từ**: ==scope== a project / feature ("Let's ==scope== this properly before committing.")
- example:
  - ==Scope== creep is the number one reason projects miss deadlines—agree on boundaries early and stick to them.
  - Before the sprint, the PM clarified which edge cases are *out of* ==scope== for this iteration.

## sprint
- phonetic: /sprɪnt/
- difficulty: 1
- categories: planning, execution
- meaning: sprint — chu kỳ phát triển ngắn trong Agile (thường 1-2 tuần)
- definition: a fixed-length iteration in Agile development during which a specific set of work is completed
- usage:
  - **Danh từ**: run / plan / start / end a ==sprint==
  - Kết hợp: ==sprint== *planning / review / retrospective*, ==sprint== *goal / backlog / velocity*
  - Giới từ: *in* the ==sprint==, *during* the ==sprint==, *at the end of* the ==sprint==
- example:
  - The ==sprint== goal for this iteration is to deliver the user notification system end-to-end.
  - During ==sprint== planning, the team selects stories from the backlog and estimates effort in story points.

## stakeholder
- phonetic: /ˈsteɪkhəʊldər/
- difficulty: 2
- categories: collaboration, communication
- meaning: bên liên quan, người có quyền lợi hoặc ảnh hưởng trong dự án
- definition: a person or group with an interest in the outcome of a project, including clients, managers, and end-users
- usage:
  - **Danh từ đếm được**: identify / engage / manage ==stakeholders==
  - Kết hợp: *key* ==stakeholders==, ==stakeholder== *management*, ==stakeholder== *alignment*
  - Giới từ: *with* ==stakeholders==, *for* ==stakeholders==
- example:
  - Present the ==stakeholders== with a clear status update every two weeks to maintain trust and alignment.
  - ==Stakeholder== management is a critical skill for any product manager or technical lead.

## strategy
- phonetic: /ˈstrætɪdʒi/
- difficulty: 2
- categories: planning, execution
- meaning: chiến lược, kế hoạch tổng thể dài hạn
- definition: a plan designed to achieve a long-term goal or competitive advantage
- usage:
  - **Danh từ**: define / execute / communicate a ==strategy==
  - Kết hợp: *technical / product / business / go-to-market* ==strategy==
  - Tính từ: *strategic* — a *strategic* decision
- example:
  - The engineering ==strategy== for this year focuses on reliability, developer experience, and reducing toil.
  - Before choosing a technology stack, define the long-term ==strategy== to ensure alignment with business goals.

## streamline
- phonetic: /ˈstriːmlaɪn/
- difficulty: 3
- categories: execution, planning
- meaning: tinh giản, tối ưu hóa quy trình để nhanh hơn và ít phức tạp hơn
- definition: to simplify and improve a process so it works more efficiently with fewer steps
- usage:
  - **V + O**: ==streamline== a process / workflow / pipeline / onboarding
  - **V2/V3**: *streamlined* / *streamlined*
  - Tính từ: a ==streamlined== process / interface
  - Kết hợp: ==streamline== *operations*, ==streamline== *the CI/CD pipeline*
- example:
  - We ==streamlined== the deployment pipeline from 12 manual steps to a single CLI command.
  - The new self-serve portal ==streamlines== the client ==onboarding== process from 5 days to under an hour.

## timeline
- phonetic: /ˈtaɪmlaɪn/
- difficulty: 1
- categories: planning, execution
- meaning: kế hoạch thời gian, dòng thời gian của dự án
- definition: a visual or written representation of events or tasks scheduled over a period of time
- usage:
  - **Danh từ**: create / set / review a ==timeline==
  - Kết hợp: *project* ==timeline==, *realistic* ==timeline==, *aggressive* ==timeline==
  - Kết hợp động từ: *on / ahead of / behind* ==schedule== (tương đương ==timeline==)
- example:
  - Share the project ==timeline== with all ==stakeholders== so everyone knows the key delivery dates.
  - The ==timeline== is too aggressive—shipping in 6 weeks without compromising quality is not realistic.

## track
- phonetic: /træk/
- difficulty: 1
- categories: execution, planning
- meaning: theo dõi, truy vết tiến độ hoặc trạng thái
- definition: to monitor and record the progress, status, or movement of something over time
- usage:
  - **V + O**: ==track== progress / bugs / metrics / performance
  - **V2/V3**: *tracked* / *tracked*
  - Kết hợp: ==track== *in Jira*, *on* ==track==, *off* ==track==, ==track== *record*
- example:
  - All feature requests and bugs must be ==tracked== in Jira with clear acceptance criteria.
  - The project is on ==track== to hit the Q4 deadline; we've completed 70% of the planned story points.

## transition
- phonetic: /trænˈzɪʃn/
- difficulty: 2
- categories: execution, planning
- meaning: chuyển đổi, quá trình chuyển từ trạng thái/hệ thống này sang trạng thái/hệ thống khác
- definition: the process of changing from one state, system, or situation to another
- usage:
  - **Danh từ**: manage / plan / lead a ==transition==
  - **Động từ**: ==transition== *from* X *to* Y ("==transition== *from* REST *to* GraphQL")
  - Kết hợp: *smooth* ==transition==, ==transition== *plan*, *gradual* ==transition==
- example:
  - The ==transition== from the legacy system to the cloud platform will be done in three phases over six months.
  - We created a detailed ==transition== plan to ensure no user data was lost during the database migration.

## update
- phonetic: /ˈʌpdeɪt/
- difficulty: 1
- categories: communication, collaboration
- meaning: cập nhật; thông báo tình hình mới nhất
- definition: (v) to make something current or communicate the latest status; (n) the latest information or version
- usage:
  - **Động từ**: ==update== the code / docs / stakeholders / a ticket
  - **Danh từ**: send / share an ==update==, a *status* ==update==
  - Kết hợp: *daily* ==update==, *software* ==update==, *provide an* ==update==
- example:
  - Please ==update== the Jira ticket status after each task so the PM can report to stakeholders accurately.
  - The team lead sent a weekly ==update== summarizing progress, risks, and next steps.

## validate
- phonetic: /ˈvælɪdeɪt/
- difficulty: 2
- categories: analysis, planning
- meaning: xác thực, kiểm chứng tính đúng đắn (dữ liệu, giả thuyết, tính năng)
- definition: to confirm that something is correct, accurate, or meets the required standard
- usage:
  - **V + O**: ==validate== input / data / assumptions / a feature
  - **V2/V3**: *validated* / *validated*
  - Danh từ: *validation* — data ==validation==, ==validation== rule
  - Kết hợp: ==validate== *before deployment*, ==validate== *with users*
- example:
  - Always ==validate== user input on both the client and server side to prevent injection attacks.
  - We ==validated== our product assumptions with 50 users before committing to a 3-month build.

## vendor
- phonetic: /ˈvendər/
- difficulty: 2
- categories: collaboration, communication
- meaning: nhà cung cấp bên ngoài (dịch vụ, công cụ, phần mềm)
- definition: an external company or individual that supplies products or services to an organization
- usage:
  - **Danh từ**: evaluate / select / manage a ==vendor==
  - Kết hợp: *third-party* ==vendor==, ==vendor== *lock-in*, ==vendor== *management*
  - Cảnh báo: *==vendor== lock-in* — khi bạn quá phụ thuộc vào một nhà cung cấp
- example:
  - Before adopting a new SaaS tool, assess the risk of ==vendor== lock-in and ensure you can export your data.
  - The security team must approve all ==vendor== contracts that involve storing customer data.

## workaround
- phonetic: /ˈwɜːkəraʊnd/
- difficulty: 2
- categories: engineering, execution
- meaning: giải pháp tạm thời, cách khắc phục khi chưa có fix chính thức
- definition: a temporary solution used to bypass a problem when the proper fix is not yet available
- usage:
  - **Danh từ**: find / implement / document a ==workaround==
  - Kết hợp: a *temporary* ==workaround==, a *quick* ==workaround==, *apply* a ==workaround==
  - Phân biệt: ==workaround== (tạm thời) vs *fix* / *patch* (lâu dài)
- example:
  - We deployed a ==workaround== to unblock clients while the root cause is being investigated.
  - Document every ==workaround== in the runbook so the on-call engineer knows what is temporary and needs a proper fix.

## workload
- phonetic: /ˈwɜːkləʊd/
- difficulty: 1
- categories: execution, planning
- meaning: khối lượng công việc phải xử lý
- definition: the amount of work that a person or system has to do
- usage:
  - **Danh từ**: manage / balance / reduce ==workload==
  - Kết hợp: *heavy / unmanageable / distributed* ==workload==, ==workload== *balance*
  - Giới từ: *under* a heavy ==workload==
- example:
  - The team's ==workload== is unsustainable—we need to either hire or cut scope for next quarter.
  - Kubernetes automatically balances ==workload== across nodes to prevent any single server from being overwhelmed.

## accountable
- phonetic: /əˈkaʊntəbl/
- difficulty: 2
- categories: collaboration, communication
- meaning: chịu trách nhiệm, phải giải trình
- definition: required to explain or justify actions and decisions; responsible for results
- usage:
  - **Tính từ**: be ==accountable== *for* results / decisions / outcomes
  - Danh từ: *accountability* — build a culture of ==accountability==
  - Kết hợp: *hold someone* ==accountable==, *personally* ==accountable==
  - Phân biệt: *responsible* (làm việc đó) vs *==accountable==* (phải trả lời nếu sai)
- example:
  - In our RACI matrix, there should be exactly one person ==accountable== for each deliverable.
  - A blameless post-mortem culture holds the *system* ==accountable==, not the individual engineer.

## transparency
- phonetic: /trænsˈpærənsi/
- difficulty: 2
- categories: communication, collaboration
- meaning: tính minh bạch, sự cởi mở về thông tin
- definition: the quality of being open and clear about processes, decisions, and information
- usage:
  - **Danh từ không đếm được**: promote / ensure / lack ==transparency==
  - Tính từ: *transparent* — be *transparent* with stakeholders
  - Kết hợp: ==transparency== *in decision-making*, *radical* ==transparency==, *build* ==transparency==
- example:
  - We publish our incident post-mortems publicly to demonstrate ==transparency== with our customers.
  - ==Transparency== about the project's risks helped us get executive buy-in for a timeline extension.

## proactive
- phonetic: /ˌprəʊˈæktɪv/
- difficulty: 2
- categories: collaboration, communication
- meaning: chủ động, tiên liệu và hành động trước khi vấn đề xảy ra
- definition: taking initiative to prevent problems or create opportunities rather than waiting to react
- usage:
  - **Tính từ**: a ==proactive== engineer / approach / stance
  - Phó từ: *proactively* — communicate *proactively*, fix issues *proactively*
  - Trái nghĩa: *reactive* — responding only after problems occur
- example:
  - A ==proactive== engineer identifies potential bottlenecks before they become production incidents.
  - Please ==proactively== communicate any blockers rather than waiting for the daily stand-up.
