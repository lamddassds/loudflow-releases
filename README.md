# LoudFlow — releases

**LoudFlow reads any text on your screen aloud, in every app.** Get it at **[loudflow.ai](https://loudflow.ai)**.
Windows and Mac are coming soon: [join the waitlist](https://loudflow.ai/download).

This repository is only the update channel of the installed app. To get LoudFlow, go to
[loudflow.ai](https://loudflow.ai), not here.

This repository carries LoudFlow's installers and nothing else. It exists so the
app can fetch its own updates without a password: GitHub serves release assets of
a public repository to anyone, and putting a token inside a shipped application
would be the alternative.

The source code is not here.

Each release contains:

| file | what it is |
|---|---|
| `LoudFlow-Setup-<version>.exe` | the Windows installer |
| `LoudFlow-Setup-<version>.exe.blockmap` | lets an installed app download only the changed blocks |
| `latest.yml` | the version the app compares itself against |
