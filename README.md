# SAA-C03 Path

A free study platform for the **AWS Certified Solutions Architect – Associate (SAA-C03)** exam, written for beginners who want to learn the material and practise at real exam difficulty.

No sign-up, no payment. Open it and start.

## The idea: learn by building one system

Most exam prep teaches AWS as a list of services. The SAA-C03 exam doesn't test definitions. It tests decisions: given a scenario and a priority, which design is best?

So this platform teaches through one story. You are the solutions architect at **PulseWire**, a news and creator startup. You take it from a single server that falls over on its first viral night to a secure, global, multi-Region platform. Each AWS service appears only when PulseWire hits the problem it solves, so you learn why a service exists and when to pick it over the alternatives.

### The cast

- **Meera**, founder and CEO. She speaks in business requirements: "never lose an article", "Europe is slow", "the bill doubled".
- **Kabir**, the only backend engineer at launch. He always asks "why can't we just…?"
- **You**, the solutions architect. In every chapter you turn Meera's problem into an architecture decision and defend it against Kabir's simpler option.

### How each chapter works

1. A problem arrives: traffic, an outage, an audit, a bill.
2. The options are laid out, one is chosen, and the others are explained away.
3. A diagram shows how the architecture changed.
4. Failure scenarios test the decision.
5. A decision tree compresses the chapter into exam reflexes.
6. Practice questions check that it stuck.

## Your path to the exam

The platform is organised as a four-step journey.

### 1. Diagnostic

Ten scenario questions, two or three from each domain. You get a score per domain and the chapters to start with, so you know where you stand before reading.

### 2. Learn

19 lessons, best read in order the first time:

| # | Lesson | What it covers |
| --- | --- | --- |
| — | How to use this guide | The cast, the method, how the exam is weighted |
| 0 | Meera's brief | Requirements, RTO and RPO |
| 1 | One server, one bad night | Single points of failure, stateless design |
| 2 | Building the neighbourhood | Regions, AZs, VPC, subnets, NAT, endpoints, hybrid connectivity |
| 3 | Who gets in, and what can they touch? | IAM, Organizations, Cognito, KMS, secrets, security services |
| 4 | Where the code runs | EC2, Auto Scaling, load balancers, Lambda, containers |
| 5 | 500,000 images a day *(focus)* | S3 and storage classes, EBS, EFS, FSx, backup, hybrid storage |
| 6 | The data heart | RDS, Aurora, DynamoDB, ElastiCache, purpose-built databases |
| 7 | Stop making the editor wait | SQS, SNS, EventBridge, Step Functions, Kinesis, API Gateway |
| 8 | "Europe is slow" | Route 53, CloudFront, Global Accelerator |
| 9 | How do we know it's working? | CloudWatch, CloudTrail, Config, automated responses |
| 10 | 50 million events a day *(focus)* | Data ingestion, data lake, Glue, Athena, Redshift, analytics |
| 11 | The acquisition | Migration strategies and services |
| 12 | Game day *(focus)* | High availability at every layer |
| 13 | When Mumbai goes dark *(focus)* | Disaster recovery strategies |
| 14 | From 100 users to the world | Scaling, stage by stage |
| 15 | The bill *(focus)* | Cost optimization and purchasing options |
| 16 | PulseWire in production | The final architecture and a design checklist |
| A | Exam reflexes | Keyword-to-service map for the last week |

Chapters marked *focus* carry the most exam weight for beginners.

Each chapter ends with three exam-style practice questions. After you answer, every option is explained, along with a one-line exam reflex to remember.

A **practice drill** lets you work through all 45 practice questions by domain, or only the ones you haven't answered or got wrong.

### 3. Mock exam

A full-length rehearsal of the real exam:

- **Format:** 65 questions in 130 minutes, with no feedback until you submit.
- **Weighting:** follows the official exam guide, with 7 multiple-response questions.

  | Domain | Weight | Questions |
  | --- | --- | --- |
  | Secure | 30% | 20 |
  | Resilient | 26% | 17 |
  | High-performing | 24% | 15 |
  | Cost-optimized | 20% | 13 |

- **Exam tools:** flag questions, jump between them with a navigator, and check a review screen before you submit. When time runs out, the exam submits automatically.
- **Resuming:** your answers are saved as you go. If you close the tab you can resume, and the clock keeps running.
- **Score:** reported on the 100–1,000 scale with 720 to pass.
- **Domain report:** in the style of the real score report ("Meets competencies" / "Needs improvement"), with the chapters to study next.
- **Answer review:** every answer can be reviewed with explanations, filtered by All, Incorrect or Flagged.

### 4. Book the real exam

Book when you pass the mock with room to spare and every domain meets competencies. Aim for 800 or more.

## How the questions are written

The questions are meant to feel like the real exam, not easier:

- **Scenario-based.** Each question has several constraints, such as cost, operational overhead, RPO/RTO or compliance.
- **Distractors that work.** Two or three options usually work technically. Only one best meets the stated priority, such as *most cost-effective*, *least operational overhead* or *highest availability*.
- **No length hints.** Option lengths are balanced, so the longest answer is not a clue. Across the question bank, the correct answer is the longest option only about 20% of the time.
- **No position hints.** Question order and answer positions are shuffled on every attempt.
- **Every option explained.** You learn why the wrong answers are wrong, which is what the exam tests.
- **Original.** Questions are written from the official exam guide and AWS documentation. None come from exam dumps, and none are real exam questions.

The 65 mock questions are separate from the 45 practice questions, so the mock stays unseen until you sit it.

## A four-week plan for beginners

About 60–90 minutes a day. If you have less time, stretch it to six weeks rather than skipping the practice questions.

| Week | Focus | What to do |
| --- | --- | --- |
| 1 | Foundations | Diagnostic, how-to, Prologue, Chapters 1–4 and their practice questions |
| 2 | Data and decoupling | Chapters 5–8; slow down on Chapter 5; drill Resilient and High-performing |
| 3 | Operations and design | Chapters 9–15; drill Cost-optimized; read the Epilogue's design checklist |
| 4 | Exam rehearsal | Appendix, the full mock in one sitting, review every miss, drill weak domains, retake |

If AWS is new to you, plan for 40–60 hours in total. If you already use it at work, 20–30.

## About the exam

| Exam detail | Value |
| --- | --- |
| Exam code | SAA-C03 |
| Questions | 65 (50 scored, 15 unscored) |
| Question types | Multiple choice and multiple response |
| Time limit | 130 minutes |
| Passing score | 720 on a 100–1,000 scale |
| Scoring | Compensatory: you pass on the overall score, not per domain |
| Fee | 150 USD |
| Delivery | Pearson VUE, online proctored or at a test centre |
| Validity | 3 years |

AWS can change these details. Check the [official exam page](https://aws.amazon.com/certification/certified-solutions-architect-associate/) before booking.

## Good to know

- **Progress stays in your browser.** Lessons read, practice answers, diagnostic and mock scores, and any exam in progress are saved in your browser only. Nothing is sent anywhere. Use the same browser to keep your progress; clearing browser data resets it.
- **The mock score is an estimate.** AWS doesn't publish its scaling formula, and the real exam includes 15 unscored questions.
- **Light and dark mode.** Follows your system setting, with a toggle in the header. Works on desktop, tablet and phone.

## Disclaimer

An independent study resource. Not affiliated with, endorsed by or sponsored by Amazon Web Services.

## Other paths

- **CLF-C02 (AWS Certified Cloud Practitioner)** is built into `index.html` alongside SAA-C03: 17 lessons (15 chapters, a how-to guide and an exam-reflexes appendix), a 10-question diagnostic, 24 practice questions by domain, and a 65-question, 90-minute mock exam scored out of 1,000 (700 to pass). Switch between SAA-C03 and CLF-C02 with the certification dropdown at the top left of any page; the site remembers your last choice, and `index.html?cert=clf` or `?cert=saa` links straight to one. Progress is saved separately for each certification. The old `clf-c02.html` link redirects to `index.html?cert=clf`.
