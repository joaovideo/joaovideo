## João Rodrigues

**Broadcast and live-event engineer, São Paulo — Brazil.** I build real-time systems for video production, and I put AI inside them.

Partner at [VENG (Vídeo Engenharia)](https://videoengenharia.com.br): professional AV, broadcast technology and technical training.

---

### The intersection

Most people who can build the model layer have never patched an audio feed under time pressure. Most people who live in vMix, NDI, SRT and SDI have never written the software that would automate it. I work in both places.

That means: live captioning and transcription, remote operations, media archive, and production automation — designed by someone who knows what happens when the deadline is the doors opening and there is no second take.

---

### Case studies

The repositories are private — these are commercial products and client systems. So I write the engineering up in public instead: architecture, the decisions behind it, the incidents, and what isn't finished yet.

| | |
|---|---|
| **[Whisper on Sanskrit](https://joao-portfolio-xdf.pages.dev/whisper-on-sanskrit)** | A live, self-correcting transcription pipeline for classes taught in three languages at once. Domain vocabulary, code-switching, local-only audio, and an output a human can verify in five seconds. |
| **[OpenRemote](https://joao-portfolio-xdf.pages.dev/openremote)** | Secure remote control across Windows, macOS, Linux, iOS and Android. Includes the production incident that destroyed fifteen days of customer data, and the four rules that came out of it. |
| **[Backup Engine](https://joao-portfolio-xdf.pages.dev/backup-engine)** | LTO tape archive in Rust, speaking raw SCSI through three operating-system backends behind one trait. Architecture study — the design is done, the engine does not yet write a tape. |

**All of them → [joao-portfolio-xdf.pages.dev](https://joao-portfolio-xdf.pages.dev)**

---

### How I work

A large share of my code is written by AI, and I disclose that everywhere. What I do is the other half: I have the idea and define what the system has to do, I choose the technology for the job, I write the instructions that direct the implementation, and then I test it against real signal, real audio and real hardware and adjust it empirically until it behaves.

That last part is not a small share of the work. A model will produce something that compiles, looks finished, and is quietly wrong — a transcription pipeline that silently drops every term it doesn't recognise, SCSI code that only fails against a real tape drive. Knowing that the output is wrong, and why, is the scarce skill, and it comes from the signal side rather than from the model.

Directing a model into production also takes more process than writing by hand, not less: a written briefing every session reads before touching anything, decision records so a model with no memory can't re-litigate a settled choice, one feature per commit, and rollback as a precondition rather than a contingency. I don't integrate code I haven't read.

---

### Stack

**Broadcast — hands-on** · vMix · NDI · SRT · SDI · FFmpeg · DeckLink

**Project stacks** · Python · Rust · Swift · TypeScript · Electron · Tauri · WebRTC · Node.js

The second line is what my projects are built in, not a claim of fluency. I own the architecture, the trust model, the reviews and what ships; the implementation is largely AI-assisted, as described above. I read every line I integrate — I don't write Rust or WebRTC unaided, and I'd rather you know that from the README than find out in the interview.

---

### Contact

[joao@video.eng.br](mailto:joao@video.eng.br) · [WhatsApp +55 11 99602-1111](https://wa.me/5511996021111)

Working in Portuguese, English and Spanish.
