# Workshop Track CMT author communication email templates

In this page you can find the review/curation decisions template and the camera-ready open announcement template.

To bulk-email authors with the submission decision, in the CMT submissions panel (make sure you have selected "Track Chair" as role in the top right), find the _Status_ field at the top of the table (scroll right, it is towards the right end), and select the corresponding group of authors you want to notify (accepted, rejected, and conditionally accepted). See the [CMT instructors on how to bulk-email authors](https://cmt3.research.microsoft.com/docs/help/chair/email-authors.html) for more details.

The templates below use the CMT placeholders (e.g. `{Submission.Id}`). You will need to replace the square brackets placeholders manually, namely:

- `[0000]` by the conference year
- `[CHAIRS NAMES]`
- `[workshops@nime0000.org]` by the chair contact emails (or a forwarding email address set up by the General Chairs, such as workshops@nime[YYYY].org)
- `[CR DEADLINE] `by camera-ready deadline
- `[OPTIONAL: ...]` --> information on decision process; use, edit or remove

Before pressing "Send", preview the email and check that the camera-ready deadline is correct and that the links work.

## Review/curation decisions

Email templates to communicate review/curation decisions to authors.

### Accept

    Subject: NIME [0000] Workshop Track - Workshop {Submission.Id} Accepted

    Dear {Recipient.Name},

    We are pleased to let you know that your workshop submission for NIME [0000] has been accepted.

    [OPTIONAL: Each submission received two reviews and a meta-review given by the Chairs, who have carefully meta-reviewed and curated the submissions.]

    {Submission.Id}
    {Submission.Title}
    {Submission.StatusName}

    Please check the submission decision in the CMT portal:
    https://cmt3.research.microsoft.com/NIME[0000]/.

    Please submit your camera-ready version in the CMT by the [CR DEADLINE].

    If you are a student, NIME is currently seeking applications from Student Volunteers to support the in-person running of the conference in {Conference.City}. In recognition of their support, Student Volunteers will have their conference registration fees waived. More information can be found on the NIME [0000] website at https://nime[0000]/call/student-volunteers/

    Please contact [workshops@NIME0000.org] if you have any questions.

    [CHAIRS NAMES]
    NIME [0000] Workshop Chairs

### Conditional accept

    Subject: NIME [0000] Workshop Track - Workshop {Submission.Id} Conditionally Accepted

    Dear {Recipient.Name},

    We are pleased to let you know that your workshop proposal for NIME [0000] has been conditionally accepted.
    [OPTIONAL: Each submission received two reviews and a meta-review given by the Chairs, who have carefully meta-reviewed and curated the submissions.]

    {Submission.Id}
    {Submission.Title}
    {Submission.StatusName}

    Please check the submission decision in the CMT portal:
    https://cmt3.research.microsoft.com/NIME[0000]/.

    Please submit your camera-ready version in the CMT by the [CR DEADLINE].

    If you are a student, NIME is currently seeking applications from Student Volunteers to support the in-person running of the conference in {Conference.City}. In recognition of their support, Student Volunteers will have their conference registration fees waived. More information can be found on the NIME [0000] website at https://nime[0000]/call/student-volunteers/

    If you do not wish to make the required changes, or have any questions about them, please contact [workshops@nime0000.org]

    [CHAIRS NAMES]
    NIME [0000] Workshop Chairs

### Reject

    Subject: NIME [0000] Workshop Track - Workshop {Submission.Id} Rejected

    Dear {Recipient.Name},

    We are sorry to inform you that your workshop proposal for NIME [0000] has not been accepted.

    [OPTIONAL: Each submission received two reviews and a meta-review given by the Chairs, who have carefully meta-reviewed and curated the submissions.] Unfortunately there were a large number of workshop submissions this year and only limited space to host them.

    You can view the submission decision in the CMT portal:
    https://cmt3.research.microsoft.com/NIME[0000]/.

    {Submission.Id}
    {Submission.Title}
    {Submission.StatusName}

    [CHAIRS NAMES]
    NIME [0000] Workshop Chairs

### Full acceptance after conditional acceptance (if requirements are satisfied in camera-ready submission)

    Subject: NIME [0000] – Workshop #{Submission.Id} full acceptance notification

    Dear {Recipient.Name},

    We are pleased to let you know that your workshop submission "{Submission.Title}" for NIME [0000] has been now fully accepted. Many thanks for incorporating the suggested changes.

    Please contact [workshops@NIME0000.org] if you have any further questions or requests.

    [CHAIRS NAMES]
    NIME [0000] Workshop Chairs

## Camera-ready form open

In NIME 2026 we sent this email as a separate email from the review/curation decision announcement, this was to avoid the authors not reading the important information regarding the camera-ready process.

### Accept

    Dear {Recipient.Name},

    Congratulations again on the acceptance of your proposal "{Submission.Title}" ({Submission.Id}) for the NIME [YYYY] Workshop track.

    The camera-ready form is now open in the CMT (https://cmt3.research.microsoft.com/NIME[YYYY]/). Please make sure you submit your camera-ready PDF and all required information before April 30th, [YYYY] (AoE).

    Before this deadline, one author will also need to register for the full conference, either in person or online; the remaining authors can register for either the full conference (online or in person) or for the workshop day only (https://nime[YYYY].org/registration/).

    Please ensure that your camera-ready submission PDF…
    – addresses the feedback given by the reviewers and the meta-reviewer.
    – uses the correct template ([Latex] nime-music-workshop-latex-template.zip or [Word] nime-music-workshop-template.docx, available in https://github.com/NIME-conference/NIME-template/releases)
    – has the appropriate sections as explained in the https://nime[YYYY].org/call/workshops/ (edit the template sections as needed)
    – includes an ethics statement
    – matches the author names and order as listed in the CMT

    You will also be asked to include an image (1000px) and short description/abstract for the online conference programme (it is fine to reuse your proposal abstract for this).

    We are aware that many of the requested items in the form are also included in the proposal document. However it makes our task as Workshop Chairs easier if you kindly include the information in the form, as we can then export all information into a spreadsheet.

    If you have any questions please contact us at [workshop@nimeYYYY.org] .

    Kind regards,
    [CHAIRS NAMES]
    NIME [YYYY] Workshop Chairs

### Conditional Accept

    Dear {Recipient.Name},

    Congratulations again on the conditional acceptance of your proposal "{Submission.Title}" ({Submission.Id}) for the NIME [YYYY] Workshop track.

    The camera-ready form is now open in the CMT (https://cmt3.research.microsoft.com/NIME[YYYY]/). Please make sure you submit your camera-ready PDF and all required information before [CR DEADLINE]

    Before this deadline, one author will need to register for the full conference, either in person or online; the remaining authors can register for either the full conference (online or in person) or for the workshop day only (https://nime[YYYY].org/registration/).

    Please ensure that your camera-ready submission PDF…
    – addresses the feedback given by the reviewers and the meta-reviewer.
    – uses the correct template ([Latex] nime-music-workshop-latex-template.zip or [Word] nime-music-workshop-template.docx, available in https://github.com/NIME-conference/NIME-template/releases)
    – has the appropriate sections as explained in the https://nime[YYYY].org/call/workshops/ (edit the template sections as needed)
    – includes an ethics statement
    – matches the author names and order as listed in the CMT

    Please ensure you submit the list of changes that were done to your proposal to address the meta-reviewers requests for full acceptance.

    You will also be asked to include an image (1000px) and short description/abstract for the online conference programme (it is fine to reuse your proposal abstract for this).

    We are aware that many of the requested items in the form are also included in the proposal document. However it makes our task as Workshop Chairs easier if you kindly include the information in the form, as we can then export all information into a spreadsheet.

    If you have any questions please contact us at [workshop@nimeYYYY.org] .

    Kind regards,
    [CHAIRS NAMES]
    NIME [YYYY] Workshop Chairs
