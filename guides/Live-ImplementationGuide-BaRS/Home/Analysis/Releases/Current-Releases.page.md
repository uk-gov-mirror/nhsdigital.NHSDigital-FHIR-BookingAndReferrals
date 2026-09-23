## Current Release 1.12.1

Product Link           | Version | Handle  | Phase    | State           | Release Date | Stability  | Change Log Link
-----------------------|---------|---------|----------|-----------------|--------------|------------|-----------------
Implementation Guide   | 1.12.0   | v1      | Live     | Current Release | 16/07/2026 | Stable     |{{pagelink:trn-General}}
[FHIR Package](https://simplifier.net/packages/uk.nhsdigital.bars.r4/1.42.0) | 1.42.0| v1      | Live     | Current Release | 16/07/2026  | Stable     |
{{pagelink:design-core-1.5.0, text:BaRS Core}}              | 1.6.0   | v1      | Live     | Current Release | 16/07/2026   | Stable     |{{pagelink:trn-core, text: BaRS Core Change Log}}
[API Specification](https://digital.nhs.uk/developer/api-catalogue/booking-and-referral-fhir/v1.5.0)    | 1.6.0   | v1      | Live     | Current Release | 16/07/2026  | Stable     |{{pagelink:trn-api}}
{{pagelink: build-testing, text: TKW}}  | 1.0.21   | v1      | Live     | Current Release | 12/11/2025   | Stable     |{{pagelink:trn-tkw}}
{{pagelink:application1, text:BaRS-APP1}}   | 2.1.0   | v1      | Live     | Current Release | 16/07/2026   | Stable     |{{pagelink:trn-app1,text:BaRS APP1 Change Log}}
{{pagelink:application2, text:BaRS-APP2}}   | 2.1.0   | v1      | Live     | Current Release | 16/07/2026   | Stable     |{{pagelink:trn-app2,text:BaRS APP2 Change Log}}
{{pagelink:application3, text:BaRS-APP3}}   | 2.0.0   | v1      | Live     | Current Release | 12/11/2025   | Stable |{{pagelink:trn-app3,text:BaRS APP3 Change Log}}
{{pagelink:application4, text:BaRS-APP4}}   | 2.0.0   | v1      | Live     | Current Release | 12/11/2025   | Stable |{{pagelink:trn-app4,text:BaRS APP4 Change Log}}
{{pagelink:application5, text:BaRS-APP5}}   | 1.2.0   | v1      | Live     | Current Release | 26/03/2026   | Stable |{{pagelink:trn-app5,text:BaRS APP5 Change Log}}
{{pagelink:application6, text:BaRS-APP6}}   | 1.0.0-beta.8 | beta      |      | Current Release | 19/05/2026   | Pre-Release |{{pagelink:trn-app6,text:BaRS APP6 Change Log}}
{{pagelink:application7, text:BaRS-APP7}}   | 1.0.0-alpha.4 | alpha      |      | Current Release | 02/07/2025  | Pre-Release |{{pagelink:trn-app7,text:BaRS APP7 Change Log}}
{{pagelink:application8, text:BaRS-APP8}}   | 1.0.0-alpha.3 | alpha      |      | Current Release | 16/07/2026  | Pre-Release |{{pagelink:trn-app8,text:BaRS APP8 Change Log}}



### Overview of the release

Release 1.12.1 of the BaRS Implementation Guide includes updates and clarifications to guidance across the standard.
 
The assurance guidance has been revised to remove the fixed “two to four weeks” timeframe. The revised guidance explains that assurance timescales depend on supplier readiness, the completeness and quality of the submission, requests for further information, required resubmissions and the resolution of issues identified during assurance.
 
Application 5 medication and allergy requirements have been clarified. References to “novel” medication and allergies have been replaced with wording that identifies medication administered or prescribed, and new allergies established, during the latest assessment. The MedicationStatement guidance now makes clear that the resource is used to carry new medication prescribed during the encounter and SHOULD NOT be used to carry medication history obtained from external sources.
 
The Core and Application change logs have been improved to distinguish Change Type from supplier Impact. This separates classifications such as Addition and Correction from information explaining what suppliers need to do as a result of a change.
 
Also included in this release are a correction to the Sentinel Element guidance for the Get Referral HTTP 503 test, corrections to external links, an update to the NHS England logo asset used by the Implementation Guide, and other minor bug fixes and corrections throughout the guide.
 
A clinical safety assessment of the scope of this release has determined that it has not significantly changed the clinical safety profile of the BaRS. No new hazards have been identified in this release. The latest version of the BaRS clinical safety case and hazard log can be downloaded from the <a href= "https://digital.nhs.uk/developer/api-catalogue/booking-and-referral-fhir/onboarding-support-information#hazard-log-and-clinical-safety-case-report-cscr-" target="_blank"> BaRS FHIR API onboarding support information page </a>.

<br>
<hr>

## Versioning Matrix

Table detailing active versions of the latest Applications in Production (or currently being built to) and their supporting Implementation Guide, Core and API versions

<table>
<thead>
	<tr>
		<th data-no-sort="">Application Version</th>
		<th data-no-sort="">Minimum BaRS Guide Version</th>
		<th data-no-sort="">Minimum Core Version</th>
		<th data-no-sort="">Minimum API Spec version</th>
	</tr>
</thead>
<tbody>
	<tr>
		<td>Application 1 v1.0.1</td>
		<td><a href="https://simplifier.net/guide/nhsbookingandreferralstandard/home?version=1.1.0" target="_blank">v1.1.0</a></td>
		<td rowspan=14 style="text-align: center; vertical-align: middle;"><a href="https://simplifier.net/guide/nhsbookingandreferralstandard/Home/Design/BaRS-Core?version=1.0.0" target="_blank">v1.0.0</a></td>
		<td rowspan=14 style="text-align: center; vertical-align: middle;"><a href="https://digital.nhs.uk/developer/api-catalogue/booking-and-referral-fhir/v1_0_0" target="_blank">1.0.0</a></td>		
	</tr>
	<tr>
		<td>Application 1 v1.0.3</td>
		<td><a href="https://simplifier.net/guide/nhsbookingandreferralstandard/home?version=1.4.0" target="_blank">v1.4.0</a></td>
	</tr>
	<tr>
		<td>Application 1 v1.0.5</td>
		<td><a href="https://simplifier.net/guide/nhsbookingandreferralstandard/home?version=1.8.0" target="_blank">v1.8.0</a></td>
	</tr>
	<tr>
		<td>Application 1 v1.0.6</td>
		<td><a href="https://simplifier.net/guide/nhsbookingandreferralstandard/home?version=1.8.1" target="_blank">v1.8.1</a></td>
	</tr>
	<tr>
		<td>Application 1 v1.0.7</td>
		<td><a href="https://simplifier.net/guide/nhsbookingandreferralstandard/home?version=1.8.2" target="_blank">v1.8.2</a></td>
	</tr>
	<tr>
		<td>Application 1 v1.0.8</td>
		<td><a href="https://simplifier.net/guide/nhsbookingandreferralstandard/home?version=1.9.0" target="_blank">v1.9.0</a></td>
	</tr>
	<tr>
		<td>Application 1 v2.0.0</td>
		<td><a href="https://simplifier.net/guide/nhsbookingandreferralstandard/home?version=1.10.0" target="_blank">v1.10.0</a></td>
	</tr>
	<tr>
		<td>Application 1 v2.1.0</td>
		<td><a href="https://simplifier.net/guide/nhsbookingandreferralstandard/home?version=1.12.0" target="_blank">v1.12.0</a></td>
	</tr>
	<tr>
		<td>Application 2 v1.0.1</td>
		<td><a href="https://simplifier.net/guide/nhsbookingandreferralstandard/home?version=1.1.0" target="_blank">v1.1.0</a></td>
	</tr>
	<tr>
		<td>Application 2 v1.0.3</td>
		<td><a href="https://simplifier.net/guide/nhsbookingandreferralstandard/home?version=1.4.0" target="_blank">v1.4.0</a></td>
	</tr>
	<tr>
		<td>Application 2 v1.0.5</td>
		<td><a href="https://simplifier.net/guide/nhsbookingandreferralstandard/home?version=1.8.0" target="_blank">v1.8.0</a></td>
	</tr>
	<tr>
		<td>Application 2 v1.0.6</td>
		<td><a href="https://simplifier.net/guide/nhsbookingandreferralstandard/home?version=1.8.1" target="_blank">v1.8.1</a></td>
	</tr>
	<tr>
		<td>Application 2 v1.0.7</td>
		<td><a href="https://simplifier.net/guide/nhsbookingandreferralstandard/home?version=1.8.2" target="_blank">v1.8.2</a></td>
	</tr>
	<tr>
		<td>Application 2 v1.0.8</td>
		<td><a href="https://simplifier.net/guide/nhsbookingandreferralstandard/home?version=1.9.0" target="_blank">v1.9.0</a></td>
	</tr>
	<tr>
		<td>Application 2 v2.0.0</td>
		<td><a href="https://simplifier.net/guide/nhsbookingandreferralstandard/home?version=1.10.0" target="_blank">v1.10.0</a></td>
	</tr>
	<tr>
		<td>Application 2 v2.0.0</td>
		<td><a href="https://simplifier.net/guide/nhsbookingandreferralstandard/home?version=1.12.0" target="_blank">v1.12.0</a></td>
	</tr>
	<tr><td>Application 3 v1.0.0</td>
		<td><a href="https://simplifier.net/guide/nhsbookingandreferralstandard/home?version=1.4.0" target="_blank">v1.4.0</a></td>
	</tr>
	<tr>
		<td>Application 3 v1.0.1</td>
		<td><a href="https://simplifier.net/guide/nhsbookingandreferralstandard/home?version=1.6.0" target="_blank">v1.6.0</a></td>
	</tr>
	<tr>
		<td>Application 3 v1.0.2</td>
		<td><a href="https://simplifier.net/guide/nhsbookingandreferralstandard/home?version=1.8.1" target="_blank">v1.8.1</a></td>
	</tr>
	<tr>
		<td>Application 3 v1.0.3</td>
		<td><a href="https://simplifier.net/guide/nhsbookingandreferralstandard/home?version=1.8.2" target="_blank">v1.8.2</a></td>
	</tr>
	<tr>
		<td>Application 3 v1.0.4</td>
		<td><a href="https://simplifier.net/guide/nhsbookingandreferralstandard/home?version=1.9.0" target="_blank">v1.9.0</a></td>
	</tr>
	<tr>
		<td>Application 3 v2.0.0</td>
		<td><a href="https://simplifier.net/guide/nhsbookingandreferralstandard/home?version=1.10.0" target="_blank">v1.10.0</a></td>
	</tr>
	<tr>
		<td>Application 4 v1.0.0</td>
		<td><a href="https://simplifier.net/guide/nhsbookingandreferralstandard/home?version=1.4.0" target="_blank">v1.4.0</a></td>
	</tr>
	<tr>
		<td>Application 4 v1.2.0</td>
		<td><a href="https://simplifier.net/guide/nhsbookingandreferralstandard/home?version=1.8.0" target="_blank">v1.8.0</a></td>
	</tr>
	<tr>
		<td>Application 4 v1.2.1</td>
		<td><a href="https://simplifier.net/guide/nhsbookingandreferralstandard/home?version=1.8.1" target="_blank">v1.8.1</a></td>
	</tr>
	<tr>
		<td>Application 4 v1.2.2</td>
		<td><a href="https://simplifier.net/guide/nhsbookingandreferralstandard/home?version=1.8.2" target="_blank">v1.8.2</a></td>
	</tr>
	<tr>
		<td>Application 4 v1.2.3</td>
		<td><a href="https://simplifier.net/guide/nhsbookingandreferralstandard/home?version=1.9.0" target="_blank">v1.9.0</a></td>
	</tr>
	<tr>
		<td>Application 4 v2.0.0</td>
		<td><a href="https://simplifier.net/guide/nhsbookingandreferralstandard/home?version=1.10.0" target="_blank">v1.10.0</a></td>
	</tr>
	<tr>
		<td>Application 5 v1.0.0-beta.4</td>
		<td><a href="https://simplifier.net/guide/nhsbookingandreferralstandard/home?version=1.4.0" target="_blank">v1.4.0</a></td>
		<td rowspan=5 style="text-align: center; vertical-align: middle;"><a href="https://simplifier.net/guide/nhsbookingandreferralstandard/Home/Core/End-to-end-workflow?version=1.4.0" target="_blank">v1.1.0</a></td>
		<td rowspan=5 style="text-align: center; vertical-align: middle;"><a href="https://digital.nhs.uk/developer/api-catalogue/booking-and-referral-fhir/v1_1_0" target="_blank">1.1.0</a></td>
	</tr>
	<tr>
		<td>Application 5 v1.0.0</td>
		<td><a href="https://simplifier.net/guide/nhsbookingandreferralstandard/home?version=1.7.0" target="_blank">v1.7.0</a></td>
	</tr>
	<tr>
		<td>Application 5 v1.1.0</td>
		<td><a href="https://simplifier.net/guide/nhsbookingandreferralstandard/home?version=1.8.0" target="_blank">v1.8.0</a></td>
	</tr>
	<tr>
		<td>Application 5 v1.1.1</td>
		<td><a href="https://simplifier.net/guide/nhsbookingandreferralstandard/home?version=1.8.1" target="_blank">v1.8.1</a></td>
	</tr>
	<tr>
		<td>Application 5 v1.1.2</td>
		<td><a href="https://simplifier.net/guide/nhsbookingandreferralstandard/home?version=1.8.2" target="_blank">v1.8.2</a></td>
	</tr>
	<tr>
		<td>Application 5 v1.1.3</td>
		<td><a href="https://simplifier.net/guide/nhsbookingandreferralstandard/home?version=1.9.0" target="_blank">v1.9.0</a></td>
	</tr>
	<tr>
		<td>Application 5 v1.1.4</td>
		<td><a href="https://simplifier.net/guide/nhsbookingandreferralstandard/home?version=1.10.0" target="_blank">v1.10.0</a></td>
	</tr>
	<tr>
		<td>Application 5 v1.2.0</td>
		<td><a href="https://simplifier.net/guide/nhsbookingandreferralstandard/home?version=1.11.0" target="_blank">v1.11.0</a></td>
	</tr>
	<tr>
		<td>Application 6 v1.0.0-beta.8</td>
		<td><a href="https://simplifier.net/guide/nhsbookingandreferralstandard/home?version=1.11.1" target="_blank">v1.11.1</a></td>
	</tr>
	<tr>
		<td>Application 7 v1.0.0-alpha.4</td>
		<td><a href="https://simplifier.net/guide/nhsbookingandreferralstandard/home?version=1.9.0" target="_blank">v1.9.0</a></td>
		<td rowspan=1 style="text-align: center; vertical-align: middle;"><a href="https://simplifier.net/guide/nhsbookingandreferralstandard/Home/Design/BaRS-Core?version=1.0.0" target="_blank">v1.0.0</a></td>
		<td rowspan=1 style="text-align: center; vertical-align: middle;"><a href="https://digital.nhs.uk/developer/api-catalogue/booking-and-referral-fhir/v1_0_0" target="_blank">1.0.0</a></td>
	</tr>
	<tr>
		<td>Application 8 v1.0.0-alpha.3</td>
		<td><a href="https://simplifier.net/guide/nhsbookingandreferralstandard/home?version=1.12.0" target="_blank">v1.12.0</a></td>
		<td rowspan=1 style="text-align: center; vertical-align: middle;"><a href="https://simplifier.net/guide/nhsbookingandreferralstandard/Home/Core?version=1.12.0" target="_blank">v1.5.0</a></td>
		<td rowspan=1 style="text-align: center; vertical-align: middle;"><a href="https://digital.nhs.uk/developer/api-catalogue/booking-and-referral-fhir/v1.5.0" target="_blank">1.5.x</a></td>
	</tr>
	<tr>
		<td></td>
		<td></td>
		<td></td>
		<td></td>
	</tr>
</tbody>
</table>


