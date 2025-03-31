**Bug Report**:

| **Bug ID** | **Title**                          | **Test Case Affected**        | **Severity** | **Status** | **Priority** | **Reported By** | **Date Reported** | **Environment** | **Test Case ID** |
| ---------- | ---------------------------------- | ----------------------------- | ------------ | ---------- | ------------ | --------------- | ----------------- | --------------- | ---------------- |
| **BR-001** | Links in Footer Missing `href` Tag | Footer Link Validation (TC10) | Medium       | Open       | Medium       | Himanshu Arya   | April 1, 2025     | Production      | TC10             |

---

**Bug Details**

| **Bug ID** | **Description**                                                                                                        | **Steps to Reproduce**                                                                                                                                                                       | **Expected Result**                                                                                                    | **Actual Result**                                                                                             | **Workaround**                                                                           |
| ---------- | ---------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- |
| **BR-001** | Footer links were missing the `href` attribute, making them non-functional and causing them to be skipped in the test. | 1. Navigate to homepage. <br> 2. Scroll to footer. <br> 3. Inspect HTML code. <br> 4. Identify links without the `href` attribute. <br> 5. Observe that these links are skipped in the test. | All footer links should have a valid `href` attribute to ensure they are clickable and functional & we have 109 links. | 27 footer links were missing the `href` attribute, making them non-functional during the test case execution. | Manually inspect and add missing `href` attributes to the links to make them functional. |

---
