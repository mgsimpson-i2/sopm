---
description: "Because having your laptop stolen should mean never having to say you're sorry."
---

# Outboard storage.

I try really, really hard not to lose data. That means that anything
of any significant value that lives on my laptop should really be
living somewhere else, in case my laptop is stolen at an airport, run
over in traffic, or otherwise rendered doorstop-ready. So:

*   I use the [Box account](https://box.internet2.edu/) that came with
    my on-boarding, along with [Box
    Edit](https://internet2.app.box.com/services/browse/official/box_edit)
    and [Box
    Drive](https://internet2.app.box.com/services/browse/official/box_drive),
    for anything that looks vaguely document-ish \(spreadsheets,
    diagrams, PDFs, etc. -- anything that isn't a web page\). I use
    Box Edit to work in shared folders or on more "organizational"
    content, and I keep a "Documents" shortcut on my desktop that
    points to a Box Drive-managed personal folder where anything more
    individual or drafty lives. Between the two, most any output that
    I generate winds up synced to Box anytime I've got an live
    Internet connection.

*   I use the ["mgsimpson-i2" account on
    Github](https://github.com/mgsimpson-i2) for any work-related
    content that is either obviously source-code-like, or that
    benefits from being treated as such \(complicated enough that I
    want proper branch or release management, or where I want to
    integrate automated workflows or change notifications into the
    editing process\). I have a "Projects" folder on my desktop; any
    subdirectory within that folder is always a local check-out of a
    Github repository, so I can always iterate a "git status" command
    across those project directories and see if I have uncommitted
    changes that would be lost if my laptop died.
  
    *   One of the private repositories under my Github account,
        "[mgsimpson-i2/org](https://github.com/mgsimpson-i2/org)",
        contains my entire org-mode hierarchy \(see the Emacs section
        on the [general purpose tools](general.md) page for more
        information\), which I check in at the end of each work day.

    *   Another private repository under the same account,
        "[mgsimpson-i2/sopm](https://github.com/mgsimpson-i2/sopm)",
        is the backing source code repository for what you're
        currently reading. Most of my editing is done through the
        Gitbook site, with changes automatically propagating as
        commits and branch-merges back to the Github backing
        store. But I keep a checkout on my laptop in case I want to do
        any bulk-editing in Emacs, or work on it offline for some
        reason.

Everything important either lives under "Documents" or "Projects" on
my desktop; I also have a "Scratch" folder that specifically indicates
"put things here if you don't care if you lose them."
