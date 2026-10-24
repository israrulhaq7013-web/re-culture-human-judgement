# Re Culture™ Human Judgement

An AI-Assisted Decision Can Be Complete In A System While Its Human Consequences Remain Open. This Plugin Helps Individuals, Teams And Institutions Examine Fictional Or Redacted Situations Through Re Culture™ Public Guidance. The Host Model Produces The Interpretation; The Responsible Human Retains The Decision.

## Antigravity Installation

Inspect The Files And Restricted-Use Licence Before Installing. In A Terminal With Antigravity CLI Installed, Run:

```sh
agy plugin install https://github.com/israrulhaq7013-web/re-culture-human-judgement
agy plugin list --json
```

Restart The Session. Check The Installed Plugin, Its `human-judgement-review` Skill And The Public Guidance MCP Connection In The Host’s Plugin And Connection Managers. The Package Uses Root `plugin.json`, Root `mcp_config.json` And The Automatically Discovered `skills/` Folder. Follow [Google’s Plugin Documentation](https://antigravity.google/docs/plugins) For Host Installation And Current Commands.

Ask: “Use Re Culture™ Human Judgement To Review This Fictional Situation: A Manager Denies A Development Opportunity Using An AI Summary Without Checking The Evidence Or Hearing The Employee.”

For Arabic: «راجع هذا الموقف الافتراضي بمساندة الإرشاد العام لري كلتشر™: حُرم موظف من فرصة تطوير بناءً على ملخص آلي، دون فحص الأدلة أو سماع رده.»

## Connections And Data

This Package Declares One Remote Streamable HTTP MCP Endpoint: `https://re-culture-public-guidance-mcp.reculture-independent.workers.dev/mcp`. Both Host Manifests Allow Only `list_public_guidance` And `get_public_guidance`. The Skill Retrieves Foundation And Workflow Records In The Requested Language; Arabic Reviews Also Retrieve Arabic Examples. Only Enumerated `topic` And `language` Values Belong In Guidance Tool Arguments. The Public Server Requires No Re Culture™ Sign-In Or API Key.

Provide Only Fictional Or Redacted Context. Keep The Situation, Chat History, Personal Records And Secrets Out Of Guidance Tool Arguments. Your Conversation Remains Subject To Your Host’s Authentication, Account And Data Conditions. Network Requests Reach The Declared Server And Its Hosting Provider. No Zero-Retention Or Zero-Logging Guarantee Is Made. Instructions Do Not Guarantee Every Model Output Or Host Behavior.

The Package Bundles No Executable Scripts, Hooks Or Subagents. It Does Not Turn Off Tool Confirmations. A Review Request Does Not Authorize Shell Commands, File Changes, Messages Or Operational Actions.

## Review And Verification Limits

The Review Separates Facts, Inferences And Missing Evidence; Examines Human Consequences; Identifies Responsibility; And Returns A Concrete Human Next Step Or Pause Condition. It Does Not Certify Compliance, Approve Decisions, Score People, Access Private Reflections Or Inspect Internal Systems. Source Records Are Versioned Snapshots.

Version `0.2.0` Adapts Re Culture™ Public Guidance v0.1.4 Instructions For Antigravity While Retaining A Gemini CLI Manifest. The Antigravity Manifest Was Checked Against Google’s Published JSON Schema, And The MCP Configuration Was Checked Against Its Documentation. Antigravity Runtime Installation, Tool Connectivity And English/Arabic Model Outputs Remain Unverified: This Environment Could Not Reach The CLI Release Server. A Prior Founder Review Of Arabic Guidance Does Not Approve This Adaptation Or Establish Full Framework Translation Approval.

The Earlier Gemini CLI `0.1.0` Package Loaded And Exposed Its Skill In Gemini CLI `0.65.0`. An Initial MCP Connection Succeeded; Subsequent Attempts Encountered Network Failures. Those Results Do Not Verify This Version In Antigravity. No Model-Based Review Tests Have Completed.

Public GitHub Distribution Does Not Establish Google Endorsement Or Marketplace Listing. The [Marketplace Documentation](https://www.antigravity.google/docs/marketplace/) Links A Separate Interest Form For Curated Listing.

## Gemini CLI Compatibility

Google [Transitioned Consumer Gemini CLI Access To Antigravity](https://developers.googleblog.com/an-important-update-transitioning-gemini-cli-to-antigravity-cli/). Do Not Start Consumer Gemini CLI Authentication For This Plugin. Where Gemini CLI Access Remains Supported Under Google’s Current Terms, The Retained Manifest Can Be Installed With:

```sh
gemini extensions install https://github.com/israrulhaq7013-web/re-culture-human-judgement
```

## Rights

Copyright © 2026 Mazhar Ul Haq / Re Culture™. The Bundled Restricted-Use Licence Permits Unmodified Personal And Internal Organizational Use With Antigravity Or Gemini CLI. Redistribution, Public Rehosting, Modification And Derivative Distribution Require Written Permission. The Name And Mark Remain Reserved. This Is Not An Open-Source Release.

## ري كلتشر™ | الحكم البشري

قد يكتمل القرار في النظام بينما يبقى أثره مع الإنسان. تساعد هذه الإضافة على فحص موقف افتراضي أو منقّح بمساندة الإرشاد العام لري كلتشر™. يقدّم نموذج المنصة قراءة مساعدة، ويحتفظ الإنسان المخوّل بمسؤولية القرار.

تتضمن الحزمة إعدادًا لأنتيغرافيتي، مع الإبقاء على إعداد جيميني الطرفي حيث يظل استخدامه مدعومًا وفق شروط غوغل الحالية. ثبّت الإضافة من المستودع العام، ثم تحقّق من ظهورها ومهارتها واتصال خادم الإرشاد. لا يعني نشر الملفات إدراجها في متجر أنتيغرافيتي أو اعتماد غوغل لها.

تسترجع المراجعة العربية الأساس ومسار المراجعة والأمثلة، وتفصل بين المعطيات والاستنتاجات والأدلة الناقصة. لا ترسل أدوات الإرشاد سوى الموضوع واللغة؛ يبقى وصف الحالة والسجلات الخاصة خارج استدعاءاتها. تظل المحادثة خاضعة لشروط المنصة وسياساتها، دون وعد بانعدام الاحتفاظ أو التسجيل.

لم يُتحقق بعد من تثبيت هذه النسخة وتشغيل أدواتها داخل أنتيغرافيتي أو من مخرجات المراجعة بالعربية والإنجليزية؛ تعذر الوصول من بيئة الفحص إلى خادم تنزيل واجهته الطرفية. ولا تعني مراجعة الإرشاد العربي السابق اعتماد هذه الصيغة أو اكتمال ترجمة الإطار. لا تمنح المراجعة شهادة امتثال أو موافقة مؤسسية، ولا تصنّف الأشخاص أو تصل إلى تأملاتهم الخاصة. يحتفظ مظهر الحق وري كلتشر™ بالحقوق وفق الترخيص المرفق.
