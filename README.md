<p align="center">
  <img src="./assets/header.svg" alt="fbirds5230 — Small fixes. Fewer surprises. A purple pixel bird against a midnight sky." width="100%">
</p>

<h1 align="center">Hey, I'm fbirds5230.</h1>

<p align="center"><b>I chase the bugs hiding in the details.</b></p>

<p align="center">
  <img src="./assets/stack.svg" alt="TypeScript, Go, and Python" width="540">
</p>

<p align="center">
  <a href="https://fbirds5230.github.io/"><b>Visit my website</b></a>
  &nbsp; / &nbsp;
  <a href="https://github.com/fbirds5230?tab=repositories"><b>Browse the code</b></a>
  &nbsp; / &nbsp;
  <a href="https://github.com/pulls?q=is%3Apr+author%3Afbirds5230"><b>Follow the patches</b></a>
</p>

<br>

I contribute focused fixes to open-source tools. Lately: process output that disappears, CSV rows that vanish, and configuration keys that refuse to behave. Every patch below comes with regression tests.

## Small patches, real problems

<table>
  <tr>
    <td colspan="2" valign="top">
      <h3><a href="https://github.com/jedib0t/go-pretty/pull/469">go-pretty</a></h3>
      <p><code>Go</code> &nbsp; <b>Merged upstream</b></p>
      <p><b>Empty still counts.</b> Keep empty single-column CSV records intact when exporting a table.</p>
      <p><a href="https://github.com/jedib0t/go-pretty/pull/469">Read the patch · #469</a></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/tinylibs/tinyexec/pull/195">tinyexec</a></h3>
      <p><code>TypeScript</code> &nbsp; <b>Merged upstream</b></p>
      <p><b>One process. Same output.</b></p>
      <p>Keep captured output available across repeated awaits and concurrent handlers.</p>
      <p><a href="https://github.com/tinylibs/tinyexec/pull/195">Read the patch</a></p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/pyscaffold/configupdater/pull/198">ConfigUpdater</a></h3>
      <p><code>Python</code> &nbsp; PR #198</p>
      <p><b>Keep the key rules consistent.</b></p>
      <p>Make validation and saving respect the document's custom option-name handling.</p>
      <p><a href="https://github.com/pyscaffold/configupdater/pull/198">Read the patch</a></p>
    </td>
  </tr>
</table>

<p><sub>My contributions to the original projects. Each card links directly to the pull request.</sub></p>

<br>

<p align="center"><b>Reproduce it. Understand it. Fix it. Leave a test.</b></p>

<p align="center">
  <img src="./assets/footer.svg" alt="" width="100%">
</p>
