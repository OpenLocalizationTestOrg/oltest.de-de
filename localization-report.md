# <a name='report-top'></a> Localization Report

## Summary
 Property | Value 
 -------- | ----- 
 Total Files | 3
[ Handoff Failed Files ](#handoff-failed-list)| 2
[ Handoff Success Files ](#handoff-success-list)| 0
[ Handback Failed Files ](#handback-failed-list)| 0
[ Out Of Sync Handback Files ](#outofsync-handback-success-list)| 0
[ In Sync Handback Files ](#insync-handback-success-list)| 0
[ Ignored Files ](#ignored-list)| 1

## <a name='handoff-failed-list'></a> Handoff Failed File List
 Source File | Status | Details 
 ----------- | ------ | ------- 
 [e2e\bf25ddc5-a055-4dcd-bda2-94b4bf16bcc5.md](https://github.com/OpenLocalizationTest/oltest/blob/b84c98714533200e1d2386b6fb46a75a5f724fcb/e2e/bf25ddc5-a055-4dcd-bda2-94b4bf16bcc5.md) | HandedOffFailed | [Details](#5851e6f623f6f31ccc2cf36eeec28eea38e715cb1)
 [e2e\f0e595ec-d68a-4abd-a87f-d07b14f3a94b.md](https://github.com/OpenLocalizationTest/oltest/blob/b84c98714533200e1d2386b6fb46a75a5f724fcb/e2e/f0e595ec-d68a-4abd-a87f-d07b14f3a94b.md) | HandedOffFailed | [Details](#885ad60b2dfe4853d48d9688db582a097734cea22)

## <a name='handoff-success-list'></a> Handoff Sucess File List

## <a name='handback-failed-list'></a> Handback Failed File List

## <a name='outofsync-handback-success-list'></a> Out Of Sync Handback Success File List

## <a name='insync-handback-success-list'></a> In Sync Handback File Success List

## <a name='ignored-list'></a> Ignored File List
 Source File | Status | Details 
 ----------- | ------ | ------- 
 [.localization-config](https://github.com/OpenLocalizationTest/oltest/blob/b84c98714533200e1d2386b6fb46a75a5f724fcb/.localization-config) | Ignored | [Details](#e4725be8631cbe979bbe0fa8b97cd75f1fd41d4d0)

## Item Details
##### <a name='e4725be8631cbe979bbe0fa8b97cd75f1fd41d4d0'></a> Source: [.localization-config](https://github.com/OpenLocalizationTest/oltest/blob/b84c98714533200e1d2386b6fb46a75a5f724fcb/.localization-config)
* Status: Ignored
* Target File: 
* Handoff File: 
* Handoff Datetime: 0001-01-01 00:00:00
* Handoff Reason: Ignored
* Handback File: 
* Handback Datetime: 0001-01-01 00:00:00
* [Back to Top](#report-top)

##### <a name='5851e6f623f6f31ccc2cf36eeec28eea38e715cb1'></a> Source: [e2e\bf25ddc5-a055-4dcd-bda2-94b4bf16bcc5.md](https://github.com/OpenLocalizationTest/oltest/blob/b84c98714533200e1d2386b6fb46a75a5f724fcb/e2e/bf25ddc5-a055-4dcd-bda2-94b4bf16bcc5.md)
* Status: HandedOffFailed
* Target File: 
* Handoff File: 
* Handoff Datetime: 0001-01-01 00:00:00
* Handoff Reason: Ignored
* Handoff Error: [handoff_transform_failed](#5851e6f623f6f31ccc2cf36eeec28eea38e715cb1handoff_transform_failed)
* Handback File: 
* Handback Datetime: 0001-01-01 00:00:00
* [Back to Top](#report-top)

##### <a name='885ad60b2dfe4853d48d9688db582a097734cea22'></a> Source: [e2e\f0e595ec-d68a-4abd-a87f-d07b14f3a94b.md](https://github.com/OpenLocalizationTest/oltest/blob/b84c98714533200e1d2386b6fb46a75a5f724fcb/e2e/f0e595ec-d68a-4abd-a87f-d07b14f3a94b.md)
* Status: HandedOffFailed
* Target File: 
* Handoff File: 
* Handoff Datetime: 0001-01-01 00:00:00
* Handoff Reason: Ignored
* Handoff Error: [handoff_transform_failed](#885ad60b2dfe4853d48d9688db582a097734cea22handoff_transform_failed)
* Handback File: 
* Handback Datetime: 0001-01-01 00:00:00
* [Back to Top](#report-top)


## Error Details
##### <a name='5851e6f623f6f31ccc2cf36eeec28eea38e715cb1handoff_transform_failed'></a> Source: [e2e\bf25ddc5-a055-4dcd-bda2-94b4bf16bcc5.md](#5851e6f623f6f31ccc2cf36eeec28eea38e715cb1)
* Error Code: handoff_transform_failed
* Error Message: Handoff source file: e2e\bf25ddc5-a055-4dcd-bda2-94b4bf16bcc5.md transformed failed.
* Retriable: False
* Error Details: {"internal_error_code":"handoff_transform_failed","internal_error_message":"Handoff source file: e2e\\bf25ddc5-a055-4dcd-bda2-94b4bf16bcc5.md transformed failed.","internal_error_retriable":false,"exception_message":"This document already has a 'DocumentElement' node.","exception_type":"System.InvalidOperationException","stack_trace":"   at System.Xml.XmlDocument.IsValidChildType(XmlNodeType type)\r\n   at System.Xml.XmlNode.AppendChild(XmlNode newChild)\r\n   at Microsoft.OpenLocalization.Helper.XliffTransformUtil.SetFileHashToXliff(String fileHash, String fileName, String xliffVersion) in E:\\caps\\OpenLocalization\\src\\OpenLocalization\\Helper\\XliffTransformUtil.cs:line 60\r\n   at Microsoft.OpenLocalization.Localization.LocalizationCore.GetHandoffFiles(GitRepo sourceRepo, GitRepo targetRepo, GitRepo handoffRepo, TranslationState translationState, TranslationOptions config, Dictionary`2 filePathInfo) in E:\\caps\\OpenLocalization\\src\\OpenLocalization\\Localization\\HandoffCore.cs:line 252","extended_information":null}

##### <a name='885ad60b2dfe4853d48d9688db582a097734cea22handoff_transform_failed'></a> Source: [e2e\f0e595ec-d68a-4abd-a87f-d07b14f3a94b.md](#885ad60b2dfe4853d48d9688db582a097734cea22)
* Error Code: handoff_transform_failed
* Error Message: Handoff source file: e2e\f0e595ec-d68a-4abd-a87f-d07b14f3a94b.md transformed failed.
* Retriable: False
* Error Details: {"internal_error_code":"handoff_transform_failed","internal_error_message":"Handoff source file: e2e\\f0e595ec-d68a-4abd-a87f-d07b14f3a94b.md transformed failed.","internal_error_retriable":false,"exception_message":"This document already has a 'DocumentElement' node.","exception_type":"System.InvalidOperationException","stack_trace":"   at System.Xml.XmlDocument.IsValidChildType(XmlNodeType type)\r\n   at System.Xml.XmlNode.AppendChild(XmlNode newChild)\r\n   at Microsoft.OpenLocalization.Helper.XliffTransformUtil.SetFileHashToXliff(String fileHash, String fileName, String xliffVersion) in E:\\caps\\OpenLocalization\\src\\OpenLocalization\\Helper\\XliffTransformUtil.cs:line 60\r\n   at Microsoft.OpenLocalization.Localization.LocalizationCore.GetHandoffFiles(GitRepo sourceRepo, GitRepo targetRepo, GitRepo handoffRepo, TranslationState translationState, TranslationOptions config, Dictionary`2 filePathInfo) in E:\\caps\\OpenLocalization\\src\\OpenLocalization\\Localization\\HandoffCore.cs:line 252","extended_information":null}


Generated by OpenLocalization.
