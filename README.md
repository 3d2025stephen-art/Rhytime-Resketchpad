# Rhytime-Resketchpad
A new tool to sketch your music in the web browser.


Rhytime — Resketchpad v0.1          





current Resketchpad workflow user-guide:


Start

New song: begin a clean blank project.
Load JSON: reopen a full Resketchpad project.
Import MIDI: bring in one MIDI source and edit it inside Resketchpad.
Browser memory restores the last work automatically.
Reload latest work: recover the previous project after New song or Clear memory.

Composing

Add notes with + note <, + note >, or + distant note.
Add silence/spacing with + Polyrest.
Notes stay magnetic by default, so the melody feels glued together.
Rests live inside/after notes as optional mute/spacing accents.
Polyrests create visible phrase room between note series.

Editing

resize latch: default note-length editing.
shift line: move phrase/line spacing using polyrests.
shift freq: edit pitch and build harmony selections.
pace spline: resize-like editing plus movement-curve reading.
analog feel gives free timing.
1/32 steps gives quantized timing.

Readings

Note tiles show pitch with black/white key labels.
Family roles mark musical meaning:open: normal note
parent: state/identity note
child: force/helper note
ruler: rhythmic/physics note

Double-click a note outside Pace mode to cycle family.
Pace mode shows parent/pivot motion as a wave spline.
Integer list checks playable/sample-aligned timing.
Singer mode shows scale-degree reading.


Hearing

Play previews the current piece in-browser.
Built-in synth has editable presets and reverb.
Synth settings save inside the song JSON.
Test sound checks the current sound quickly.
Tempo can use native, custom, or MIDI source tempo.
Harmony
In shift freq, click notes into the harmony palette.
Use Tonic arrange, Chord seedbag, or Tessitura tool to explore harmonic options.
Next synth cycles selected notes through suggested results.
Save Safely
Undo / Redo cover edits.
Browser autosave keeps the current project locally.
Save JSON is the rich portable project file.
Export MIDI sends notes to MIDI/DAW tools.
Clear memory clears current browser autosave but keeps latest work recoverable.



 *Development Note*

    Resketchpad was designed and directed by the author. During
    development, AI-assisted coding tools were used to help prototype
    features, generate implementation suggestions, review code, and
    accelerate development. All design decisions, feature selection,
    testing, and final integration were performed under the author's
    direction.

Based on writing music on paper in another kind.


The MIDI support is important because it makes the tool interoperable,
but the real value is that it forced the formalized note/rest
model. 
That foundation will make future features—like in Rhytime
notation, movement library, and pattern zones—much easier to build
because they're all describing the same underlying musical structure
rather than separate systems.




 - Rhytime — Resketchpad v0.1 license

*No public free or commercial redistribution of our UI.


*Redistribution, when authorized by the copyright holder, you
    preserve this project, code, this license, and proper authoring attribution sharable.*


*We must preserve this license and provide
    complete corresponding source code to redistribute.
 Public releases require prior
    written permission from the copyright holder.


*The goal of this project is to help the learning, experimentation,
    and contribution to the musical tool while preserving a single official distribution.*



We apreciate contributions.

 keeping the project coherent as a *"stewarded source-available project"* never a closed project.

people can extend the tool and ask to publish a version even commercial once valid under the term of source so

------------------------------------------------------------------------


*If permission to publicly redistribute or commercially publish a
    derivative is granted, the derivative author retains copyright to
    their own original modifications. The original author retains
    copyright to the original project. Authorized derivative authors
    agree to provide the original author with a copy of the released
    version for archival, compatibility, and possible inclusion in the
    official project.


      Source Available License (summary)

You may:


    Study and learn from the source code.

    Modify the software for personal and educational use.

    Develop improvements, extensions, and new modules.

    Share the source privately with collaborators working on the same
    project.

    Contact the author to request permission to publish or commercially
    distribute your derivative work.

You may not:


    Publicly redistribute the software UI, UX, scripts, whether free or commercial,
    without prior written permission.

    Publish modified versions without permission.

    Use the project, source code, documentation, presets, examples, or
    assets to train, fine-tune, benchmark, or improve AI or machine
    learning systems without prior written permission.

------------------------------------------------------------------------
No public free/commercial redistribution beyond this license


    *Develop improvements, extensions, and new modules.*

That invites developers to contribute instead of discouraging them.

Then the publication step becomes a discussion rather than an automatic
right.



*Development Note*

    Resketchpad was designed and created by the author. For the
    development AI-assisted coding tools were used to prototype
    features, generate implementations, review code, and
    accelerate the development.



Based on our method to write music by hand in another kind.

 All design decisions, feature selection, theories,
    testing, and final integration were performed under the author's direction.

The MIDI support is important because it makes the tool interoperable, reloadable,
but the real value is that it forced the formalized note/rest
model. 
That foundation will make future features—like in Rhytime
notation, movement library, and pattern zones—much easier to build
because they're all describing the same underlying musical structure
rather than separate systems.



Resketchpad reflects the music writers by making rhythm, silence, and melodic
movement editable by the musician, the software will handle
things like file formats, timeline organization, and playback. To gives the user
 both efficiency and creative ownership.



