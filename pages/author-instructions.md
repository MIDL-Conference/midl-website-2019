---
title: "Author instructions"
---

# Author instructions

Conference submissions follow two tracks: *full conference papers* and *extended abstracts*.
All accepted full papers will be published as a volume in the [Proceedings of Machine Learning Research](http://proceedings.mlr.press/).
The best full papers will also be invited for submission to a special issue of [Medical Image Analysis](https://www.journals.elsevier.com/medical-image-analysis), a top journal in the field.

## Extended abstracts

Extended abstracts are up to 3 pages (excluding references and acknowledgements) and can, for example, focus on preliminary novel methodological ideas without extensive validation. We also specifically accept extended abstracts of recently published or submitted journal contributions to give authors the opportunity to present their work and obtain feedback from the community. Selection of abstracts is performed via a lightweight single-blind review process via OpenReview. All accepted abstracts will be presented as posters at the conference.

**Submission deadline:** 17 April 2019, 17:00 UTC

## Full papers

Full papers contain well-validated applications or methodological contributions of deep learning algorithms in medical imaging. There is no strict limit on paper length. However, we strongly recommend keeping full papers at 8 pages (excluding references and acknowledgements). An appendix section can be added if needed with additional details but must be compiled into a single PDF. The appropriateness of using pages over the recommended page length will be judged by reviewers. Full papers will go through a single-blind peer-reviewing process via OpenReview. All accepted papers will be presented as posters with a selection of these papers will also be invited for oral presentation.

**Submission deadline:** 17 December 2018, 17:00 UTC

---


## Latex template

To prepare your submission to MIDL 2019 either as a full paper or an extended abstract, please use the LaTeX style files provided at:
https://github.com/MIDL-Conference/MIDLLatexTemplate

## Dual submission policy

### Full papers

Submissions that are substantially similar or identical to versions that have been previously published, or accepted for publication, or that have been submitted in parallel to other conferences with proceedings or journals, are not allowed.

### Extended abstracts

In addition to original work, authors can choose to submit a shortened version of a recently (within the year 2018 or 2019) published, or submitted, journal publication to foster dissemination of high-quality work. Submissions that are substantially similar or identical to versions that have been accepted or submitted in parallel to other conferences with proceedings are not allowed.

In both cases, dual submission of your paper to a non-peer reviewed website like arXiv is allowed. Similarly, submissions that have been presented at non-archival workshops (i.e., venues that do not have publication proceedings or publish only a very short abstract) do not violate the policy.

The policy is enforced during the whole reviewing process period.

## Withdrawing policy and rejected papers

Authors have the right to withdraw papers from consideration at any time until the paper submission deadline. After the submission deadline and during the paper review process, it will not be possible to withdraw a paper. After the decisions are announced, it will be possible for authors to withdraw a rejected paper. At any stage, if an author withdraws the paper, it will be deleted from the OpenReview hosting site.

---

## Reviewing process

1. Submissions to MIDL can be made either as a full paper or as an extended abstract.
2. Submissions to MIDL are uploaded on OpenReview, which enables public discussion. Official reviews are anonymous and publicly visible. However, reviews from the Public (=anybody who is logged in can post comments) will only be released after the decisions are announced. The author of a comment can decide to post anonymously or not. Login is required before posting any comment.
3. Submissions to MIDL will be single-blind by default, where the author names will be visible. However, if the authors choose to submit anonymously (in a double-blind fashion), this option is also permitted.
4. Extended abstract submissions will undergo a lighter review.
5. By January 28, 2019, reviewers need to post their full review. Official reviews are anonymous by default and publicly visible in Open Review
6. The rebuttal and discussion period will be from January 28, 2019 until February 10, 2019, where authors can address reviewer comments.
7. On February 20, 2019, authors will be notified about the acceptance or rejection of their paper.
8. Papers that are not accepted will be considered non-archival, and may be submitted elsewhere at the discretion of the authors. We strongly encourage taking into account the reviewers comments before resubmitting. During submission, the authors will have the option to indicate whether to have their submissions, the reviews, and the comments to be deleted from the OpenReview site, in case their submission is rejected.

---

## Camera-ready instructions

**Applies only to full papers.**

Please ensure your latex project has the following features:

1. The main tex file should be named "surname19.tex", where "surname" is replaced with the primary author’s surname. The number 19 represents 2 digit representation of the year of publication. This naming convention is necessary as per the PMLR format.
2. The bibliography should be in a single .bib file and named "surname19.bib" with the same convention as above.
3. Within the "surname19.tex" tex file, the document class should be:
   <pre><code>\documentclass{midl}</code></pre>
4. You should also set the following variables before the \title command:
   <pre><code>\jmlrvolume{-- XXXX}<br>\jmlryear{2019}<br>\jmlrworkshop{Full Paper -- MIDL 2019}</code></pre>
5. The bibliography should be included in the paper using the following command:
   <pre><code>\bibliography{surname19}</code></pre>
6. Please do NOT use the `\begin{thebibliography}` environment.
7. Do not use any `\vskip` or any other format/spacing altering commands. They will be removed during compilation.
8. Fill out the PMLR Publication Agreement and upload it in PDF format to Overleaf as part of your project.

Please note that all of the above is necessary for the publication of your paper in the PMLR proceedings.

Submission of all necessary source files will happen through Overleaf. Upload your project to Overleaf, giving it the name surname19. Make sure that your source files compile correctly on Overleaf, and share the project with the email [b.glocker@imperial.ac.uk](mailto:b.glocker@imperial.ac.uk) as a collaborator. You also need to submit the final paper in PDF format in OpenReview using the "Add Revision" button.

---

## Preparing your presentation

### Poster presentations

The **poster size is A0 portrait** format (841 × 1189 mm or 33.11 × 46.81 inches width and height).

All accepted full papers and abstracts will be presented as posters at the conference. Posters of full papers will stay up throughout the three days of the main conference. Posters of abstracts will be up for one day. Each poster will be assigned to one of three poster sessions. During the assigned poster session, one of the authors must be present at the poster.

Full paper posters and the Monday abstract posters should be mounted between 9:00am and 9:30am on Monday, July 8. Tuesday and Wednesday abstract posters should be mounted between 8:30am and 9:00am on their respective allocated day. Monday and Tuesday abstract posters must be taken down at the end of their respective day, all other posters must be taken down by Wednesday 2:30pm. Posters left behind will be discarded.

### Oral Presentations

The preferred formats are PowerPoint and Adobe PDF. Presenters will be required to use the conference system to minimize setup time. The system will run Windows 10 with the latest PowerPoint. Please prepare your slides in 16:9 aspect ratio. If a PowerPoint presentation includes a video, we strongly recommend using .mp4 files encoded with H.264 video and AAC audio (if any) to minimise potential compatibility issues.

Oral presentations are either a long oral or a spotlight short talk:

* **Long orals must not exceed 18 minutes, leaving 5 minutes for questions.**
* **Each spotlight talk is allocated a 3 minute slot, without time for question.**

Timing will be strictly enforced to ensure a smooth handover between speakers. Please ensure that you have rehearsed the timing of your talk beforehand. As a rule of thumb, you should have one slide per minute of talk time. The session chair will introduce each speaker and title of the talk. Each oral presentation will also have an associated poster presentation, and therefore any additional details can be provided at that time.