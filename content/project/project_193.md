{
  "Title": "physiopy/phys2bids: BIDS formatting of physiological recordings",
  "issue_number": 193,
  "link_to_issue": "https://github.com/ohbm/hackathon2020/issues/193",
  "labels": [
    {
      "name": "Americas hub",
      "description": "",
      "color": "ffaac8"
    },
    {
      "name": "BIDS",
      "description": "some knowledge of BIDS required",
      "color": "562caa"
    },
    {
      "name": "EMEA hub",
      "description": "",
      "color": "b8aeef"
    },
    {
      "name": "Hackathon project",
      "description": "use this tag for submitted projects",
      "color": "fcffbc"
    },
    {
      "name": "Missing reg",
      "description": "",
      "color": "fbca04"
    },
    {
      "name": "eye tracking",
      "description": "eye tracking electrical data",
      "color": "f7e5b9"
    },
    {
      "name": "git-0",
      "description": "no prior git knowledge required",
      "color": "00ff00"
    },
    {
      "name": "machine learning",
      "description": "",
      "color": "15c1b9"
    },
    {
      "name": "physiological data",
      "description": "physiological recording data",
      "color": "bfd4f2"
    },
    {
      "name": "python",
      "description": "some knowledge of python required",
      "color": "fc8397"
    },
    {
      "name": "reStructuredText",
      "description": "reStructuredText documentation syntax",
      "color": "e53b68"
    }
  ],
  "content": "**Guidelines**\r\n\r\n*We are very excited to meet you at the 2020 OHBM Brainhack \ud83c\udf89* *To submit a project, you need to be an attendee of the 2020 OHBM Brainhack. We ask you to register first over [here](http://www.humanbrainmapping.org/HackathonReg/). Thank you!*\r\n\r\n*We have prepared a checklist to help with your project submission. Here is how to proceed:*\r\n 1. *Before filling in any part, please submit this issue*\r\n 2. *Check items in the checklist below as you go through them*\r\n 3. *Once you are done (at least all 'required' items must be provided), please delete the \"Guidelines\" section add a comment saying 'hi @ohbm/project-monitors: My project is ready!'*\r\n\r\nThank you!\r\n\r\n*After step 1 (issue submitted), we will assign a 'project monitor' to follow your submission. If at any time you need help or anything is unclear, please add a comment and ping your project monitor. Our team is here to help!*\r\n\r\n\r\n----------------------------\r\n## Project info\r\n<!-- *Please fill this in first and then submit the issue* -->\r\n\r\n**Title**: physiopy/phys2bids: BIDS formatting of physiological recordings\r\n<!--Name of your awesome project. Please also update the title of the issue to be the title of your project-->\r\n\r\n**Project lead**: Vicente Ferrer @vinferrer (EMEA), Eneko Uru\u00f1uela @eurunuela (EMEA), Fran\u00e7ois Lespinasse @sangfrois (The Americas), Stefano Moia @smoia (EMEA, The Americas)\r\n<!--Your name and GitHub login, possibly more than 1 lead-->\r\n\r\n**[Timezone](https://github.com/ohbm/hackathon2020/blob/master/.github/ISSUE_TEMPLATE/handbooks/projects.md#timezone)**: Berlin, Brussels UTC+2\r\n<!--UTC offset of your timezone (cf. https://www.timeanddate.com/time/map/ for example).-->\r\n\r\n**Hub**: EMEA / The Americas\r\n<!--Asia and Pacific / Europe, Middle East and Africa / The Americas based on location of project lead. Possibly more than 1 hub.-->\r\n\r\n**Description**:\r\n[Physiopy](https://github.com/physiopy) is a github organisation maintained by (at the moment) 12 volunteers that aims to offer open development solutions for physiology in MRI.\r\n[`phys2bids`](https://github.com/physiopy/phys2bids) is the flagship library of physiopy, and consists in a python3 library meant to format physiological (cardiac, respiratory, or gas signals) files in BIDS. It was born for AcqKnowledge (BIOPAC) files, and at the moment it also supports LabChart (ADInstruments). It doesn\u2019t support physiological files recorded with the MRI (yet).\r\nNext to `phys2bids`, we\u2019re starting the development of [`phys2denoise`](https://github.com/physiopy/phys2denoise), a library dedicated to prepare physiological signal for fMRI denoising.\r\n\r\n<!--Describe the main idea and context of your project in a few sentences.-->\r\n\r\n**Link to project**: https://github.com/physiopy/phys2bids\r\n\r\n**Mattermost handle**: @smoia\r\n\r\n**Goals for the OHBM Brainhack**\r\nWe have different proposals for Brainhack participants, that can be seen [here](https://github.com/physiopy/phys2bids/milestone/5).\r\nBetween the contributors, we have very different background, but one that is lacking is knowledge in pattern recognition or ML. We\u2019d be thrilled if someone that has experience in that field could help us set up an automatic recognition of the file contents!\r\nWe would also like to start supporting eyetracking bidsification, so if anyone with background (and recordings) in eyetracking wants to help out, it would be a great opportunity to work together.\r\nWe\u2019re always looking forward for collaboration with other bidsificators. At the moment, we\u2019re working together with  `bidscoin` to integrate the two solutions together, and we\u2019d be happy to start a dialogue with `heudiconv` contributors and other bidsificators too!\r\n\r\n**Good first issues**:\r\nSee them [here](https://github.com/physiopy/phys2bids/labels/Good%20first%20issue)\r\n\r\n**Skills**: Depending on the issue that you want to tackle!\r\n\r\n- Good First Issues: willingness to learn python/git/github/restructured text. We\u2019ll help you out with those!\r\n- Automatic recognition of physiological signal: knowledge of pattern recognition in python is welcomed.\r\n- Eyetracking integration: knowledge of eye tracking (python knowledge not necessary).\r\n- Making a report for phys2bids: interest in design or UI/UX or web design skills.\r\n- If you\u2019re a BIDS expert, we\u2019d love to have a chat with you!\r\n- Other required skills are described in the issues themselves.\r\n\r\n**Chat channel**:  [#hbmhack-physiopy](https://mattermost.brainhack.org/brainhack/channels/physiopy)\r\n\r\n<!-- If you are creating a channel on the [brainhack mattermost](https://mattermost.brainhack.org/) try to create a\r\n**public** channel with one of the following template names:\r\n\r\n- hbmhack-NAME_OF_YOUR_PROJECT\r\n- hbm-NAME_OF_YOUR_PROJECT\r\n\r\nThese would be the corresponding URLs that you can paste here.\r\n\r\nhttps://mattermost.brainhack.org/brainhack/channels/hbmhack-NAME_OF_YOUR_PROJECT\r\nhttps://mattermost.brainhack.org/brainhack/channels/hbm-NAME_OF_YOUR_PROJECT\r\n-->\r\n\r\n\r\n**Video channel**: will be provided in the mattermost channel.\r\n<!--\r\nWe are trying to be super careful about \"zoom bombing\" possibility.\r\nSo we want to avoid having links to video chats in \"public space\".\r\nWe suggest that you create a Jitsi or Zoom room and mention it in your text channel as \"pinned\" message or in the channel header.\r\n\r\n-->\r\n\r\n**Image for the OHBM brainhack website**\r\nhttps://github.com/physiopy/phys2bids/blob/master/docs/_static/phys2bids_card.jpg\r\n\r\n**Contribution recognition**: We follow all-contributors specifications! See [here](https://github.com/physiopy/phys2bids#contributors-)\r\n\r\n*Important documents*: Start with [this page](https://phys2bids.readthedocs.io/en/latest/contributing.html), \r\n\r\n## Project submission\r\n\r\n## Submission checklist\r\n*Once the issue is submitted, please check items in this list as you add under 'Additional project info'*\r\n\r\nPlease include the following above (all required):\r\n-   [x] Link to your project: could be a code repository, a shared document, etc. See [here](https://github.com/ohbm/hackathon2020/blob/master/.github/ISSUE_TEMPLATE/handbooks/projects.md#link-to-project)\r\n-   [x] Include your [Mattermost handle](https://mattermost.brainhack.org/) (i.e. your username). If you do not have an account, please [sign up here](https://mattermost.brainhack.org/signup_email).\r\n-   [x] Goals for the OHBM Brainhack: describe what you want to achieve during this brainhack. See [here](https://github.com/ohbm/hackathon2020/blob/master/.github/ISSUE_TEMPLATE/handbooks/projects.md#goals).\r\n-   [x] Flesh out at least 2 \"good first issues\": those are tasks that do not require any prior knowledge about your project, could be defined as issues in a GitHub repository, or in a shared document, cf [here](https://github.com/ohbm/hackathon2020/blob/master/.github/ISSUE_TEMPLATE/handbooks/projects.md#onboarding-2-good-first-issues).\r\n-   [x] Skills: list skills that would be particularly suitable for your project. We ask you to include at least one non-coding skill, cf. [here](https://github.com/ohbm/hackathon2020/blob/master/.github/ISSUE_TEMPLATE/handbooks/projects.md#onboarding-skills).\r\n-   [x] Chat channel: A link to a chat channel that will be used during the OHBM Brainhack. This can be an existing channel or a new one. We recommend using the [Brainhack space on mattermost](https://mattermost.brainhack.org/), cf. [here](https://github.com/ohbm/hackathon2020/blob/master/.github/ISSUE_TEMPLATE/handbooks/projects.md#chat).\r\n-   [x] Video channel: Please create a video channel that will be used during the OHBM Brainhack and share it in your chat channel above. This can be an existing channel or a new one. For instance a [jitsi meet](https://meet.jit.si/) room, cf. [here](https://github.com/ohbm/hackathon2020/blob/master/.github/ISSUE_TEMPLATE/handbooks/projects.md#video-calls).\r\n-   [x] Provide an image of your project for the OHBM brainhack website\r\n\r\nYou can also include information about (all optional):\r\n-   [ ] Number of participants, cf. [here](https://github.com/ohbm/hackathon2020/blob/master/.github/ISSUE_TEMPLATE/handbooks/projects.md#participant-capacity)\r\n-   [ ] Twitter-size summary of your project pitch, cf. [here](https://github.com/ohbm/hackathon2020/blob/master/.github/ISSUE_TEMPLATE/handbooks/projects.md#twitter-size-summary-of-your-project-pitch)\r\n-   [ ] Set up a kanban board on your repository to better divide the work and keep track of things, cf [here](https://github.com/ohbm/hackathon2020/blob/master/.github/ISSUE_TEMPLATE/handbooks/projects.md#set-up-a-kanban-board)\r\n-   [x] Project snippet for the OHBM Brainhack website, cf. [here](https://github.com/ohbm/hackathon2020/blob/master/.github/ISSUE_TEMPLATE/handbooks/projects.md#project-snippet-for-the-ohbm-brainhack-website)\r\n\r\nWe would like to think about how you will credit and onboard new members to your project. We recommend reading references from [this section](https://github.com/ohbm/hackathon2020/blob/master/.github/ISSUE_TEMPLATE/handbooks/projects.md#credit-and-onboarding). If you'd like to share your thoughts with future project participants, you can include information about (recommended):\r\n-   [x] Specify how will you acknowledge contributions (e.g. listing members on a contributing page).\r\n-   [x] Provide links to onboarding documents if you have some.\r\n"
}