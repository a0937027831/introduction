# IBA Interview 2024

Thank you for participating in our interview process. This repository provides instructions on how to complete and submit your answers for the technical challenge. The challenge is divided into two parts: a TypeScript Challenge and a Frontend Challenge (you can choose between Vue and React).

## Part 1: TypeScript Challenge

### Instructions
1. Open the provided [CodeSandbox]([https://codesandbox.io/s/your-codesandbox-link](https://codesandbox.io/p/sandbox/divine-wood-hrtvsn?layout=%257B%2522sidebarPanel%2522%253A%2522EXPLORER%2522%252C%2522rootPanelGroup%2522%253A%257B%2522direction%2522%253A%2522horizontal%2522%252C%2522contentType%2522%253A%2522UNKNOWN%2522%252C%2522type%2522%253A%2522PANEL_GROUP%2522%252C%2522id%2522%253A%2522ROOT_LAYOUT%2522%252C%2522panels%2522%253A%255B%257B%2522type%2522%253A%2522PANEL_GROUP%2522%252C%2522contentType%2522%253A%2522UNKNOWN%2522%252C%2522direction%2522%253A%2522vertical%2522%252C%2522id%2522%253A%2522clyvbq7q700063578iyg2t1pi%2522%252C%2522sizes%2522%253A%255B100%255D%252C%2522panels%2522%253A%255B%257B%2522type%2522%253A%2522PANEL_GROUP%2522%252C%2522contentType%2522%253A%2522EDITOR%2522%252C%2522direction%2522%253A%2522horizontal%2522%252C%2522id%2522%253A%2522EDITOR%2522%252C%2522panels%2522%253A%255B%257B%2522type%2522%253A%2522PANEL%2522%252C%2522contentType%2522%253A%2522EDITOR%2522%252C%2522id%2522%253A%2522clyvbq7q600023578gsi1ej1i%2522%257D%255D%257D%252C%257B%2522type%2522%253A%2522PANEL_GROUP%2522%252C%2522contentType%2522%253A%2522SHELLS%2522%252C%2522direction%2522%253A%2522horizontal%2522%252C%2522id%2522%253A%2522SHELLS%2522%252C%2522panels%2522%253A%255B%257B%2522type%2522%253A%2522PANEL%2522%252C%2522contentType%2522%253A%2522SHELLS%2522%252C%2522id%2522%253A%2522clyvbq7q600033578hih9fqcu%2522%257D%255D%252C%2522sizes%2522%253A%255B100%255D%257D%255D%257D%252C%257B%2522type%2522%253A%2522PANEL_GROUP%2522%252C%2522contentType%2522%253A%2522DEVTOOLS%2522%252C%2522direction%2522%253A%2522vertical%2522%252C%2522id%2522%253A%2522DEVTOOLS%2522%252C%2522panels%2522%253A%255B%257B%2522type%2522%253A%2522PANEL%2522%252C%2522contentType%2522%253A%2522DEVTOOLS%2522%252C%2522id%2522%253A%2522clyvbq7q6000535789ehah9cl%2522%257D%255D%252C%2522sizes%2522%253A%255B100%255D%257D%255D%252C%2522sizes%2522%253A%255B100%252C0%255D%257D%252C%2522tabbedPanels%2522%253A%257B%2522clyvbq7q600023578gsi1ej1i%2522%253A%257B%2522id%2522%253A%2522clyvbq7q600023578gsi1ej1i%2522%252C%2522activeTabId%2522%253A%2522clyvbq7q600013578gj35c8n9%2522%252C%2522tabs%2522%253A%255B%257B%2522id%2522%253A%2522clyvbq7q600013578gj35c8n9%2522%252C%2522mode%2522%253A%2522permanent%2522%252C%2522type%2522%253A%2522FILE%2522%252C%2522filepath%2522%253A%2522%252FREADME.md%2522%252C%2522state%2522%253A%2522IDLE%2522%252C%2522initialSelections%2522%253A%255B%257B%2522startLineNumber%2522%253A22%252C%2522startColumn%2522%253A6%252C%2522endLineNumber%2522%253A22%252C%2522endColumn%2522%253A6%257D%255D%257D%252C%257B%2522type%2522%253A%2522FILE%2522%252C%2522filepath%2522%253A%2522%252Fbem.ts%2522%252C%2522id%2522%253A%2522clyvbuojx002v3578e6gbfmt3%2522%252C%2522mode%2522%253A%2522temporary%2522%252C%2522state%2522%253A%2522IDLE%2522%257D%255D%257D%252C%2522clyvbq7q6000535789ehah9cl%2522%253A%257B%2522id%2522%253A%2522clyvbq7q6000535789ehah9cl%2522%252C%2522activeTabId%2522%253A%2522clyvexr9p000v35787lxvvtvb%2522%252C%2522tabs%2522%253A%255B%257B%2522id%2522%253A%2522clyvbq7q600043578124bflvq%2522%252C%2522mode%2522%253A%2522permanent%2522%252C%2522type%2522%253A%2522UNASSIGNED_PORT%2522%252C%2522port%2522%253A0%252C%2522path%2522%253A%2522%252F%2522%257D%252C%257B%2522type%2522%253A%2522CHANGELOG%2522%252C%2522id%2522%253A%2522clyvbva2e00403578ipxat0do%2522%252C%2522mode%2522%253A%2522permanent%2522%257D%252C%257B%2522type%2522%253A%2522DOCS%2522%252C%2522path%2522%253A%2522%252Feditors%252Fweb%252Fvscode-web%2522%252C%2522id%2522%253A%2522clyvexjt300073578ddxq5j14%2522%252C%2522mode%2522%253A%2522permanent%2522%257D%252C%257B%2522type%2522%253A%2522SANDBOX_INFO%2522%252C%2522isCloud%2522%253Afalse%252C%2522id%2522%253A%2522clyvexr9p000v35787lxvvtvb%2522%252C%2522mode%2522%253A%2522permanent%2522%257D%255D%257D%252C%2522clyvbq7q600033578hih9fqcu%2522%253A%257B%2522tabs%2522%253A%255B%255D%252C%2522id%2522%253A%2522clyvbq7q600033578hih9fqcu%2522%257D%257D%252C%2522showDevtools%2522%253Afalse%252C%2522showShells%2522%253Afalse%252C%2522showSidebar%2522%253Atrue%252C%2522sidebarPanelSize%2522%253A15%257D)) link which contains all the necessary files for the challenge.
2. Fork the CodeSandbox to your account.
3. Complete the three TypeScript questions provided in the sandbox.
4. Ensure all your changes are saved and the code runs as expected.

## Part 2: Frontend Challenge

### Instructions
1. Choose **one** of the following repositories to complete the Frontend Challenge:
   - [Vue Repository](https://github.com/iba-interview/implement-vue)
   - [React Repository](https://github.com/iba-interview/implement-react)
2. Fork the chosen repository to your GitHub account.
3. Follow the instructions in the repository's README to complete the challenge.
4. Ensure all your changes are committed and pushed to your forked repository.

## Submission

Once you have completed both parts of the challenge, submit the links to your forked repositories to HR. Please make sure to double-check your work before submission.

### Example Submission
```markdown
**TypeScript Challenge:** [CodeSandbox Link](https://codesandbox.io/s/your-forked-codesandbox-link)
**Frontend Challenge:** [GitHub Repository Link](https://github.com/your-username/forked-repo-link)
```

We look forward to reviewing your submission. Good luck!

Should you have any questions or encounter any issues during the challenge, feel free to reach out to HR for assistance.
