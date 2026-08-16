<!--
SPDX-FileCopyrightText: 2026 The .github development team

SPDX-License-Identifier: GPL-3.0-or-later
-->

<div align="center">
  <a href="https://github.com/ReLi-Framework">
    <!-- markdownlint-disable-next-line line-length -->
    <img src="../assets/images/logo.svg" alt="Logo" />
  </a>

<h3 align="center">ReLi Framework</h3>
</div>

## :warning: Disclaimer

All projects in this organization are intended for **legal use only**. We are
not responsible for any misuse, abuse, or harmful derivative work built from
them.

## :eyes: About the organization

[ReLi Framework] builds open source infrastructure for managing
configurable offensive tooling.

Its main project, [ReLi], helps teams keep offensive tools,
configuration, and construction logic inside the projects that own them, while
providing a common framework around their lifecycle.

This makes it easier to integrate new tools, maintain controlled variants, and
support richer configuration strategies such as recompilation without forcing
every project into the same builder model.

### :question: Why

[Traditional offensive builders][lockbit builder] work well for one tool, but
they do not scale cleanly when every new project brings its own configuration
and build logic.

[ReLi] reduces that maintenance surface by moving those responsibilities
back into the tool's project instead of spreading them across custom builders and
platform code.

It also fits better with standard development practices and enables richer
configuration strategies such as recompilation.

[lockbit builder]: https://securelist.com/lockbit-ransomware-builder-analysis/110370/
[reli]: https://github.com/ReLi-Framework/ReLi/
[reli framework]: https://github.com/ReLi-Framework/
