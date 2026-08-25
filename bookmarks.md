# Personal Bookmarks

> [!NOTE]
> This file is tracked in Git to ensure it is safely backed up and won't be lost, but it is **not** linked on any public-facing HTML pages. A `.nojekyll` file is configured at the repository root to prevent GitHub Pages from automatically compiling or publishing markdown files.

---

## Researchers & Applied Science

### [Ilaria Chillotti](https://ilachill.github.io/)
- **URL**: https://ilachill.github.io/
- **Topics**: Cryptology, Fully Homomorphic Encryption (FHE), Multi-Party Computation (MPC)
- **The Core Idea / Research Significance**:
  - **Fully Homomorphic Encryption (FHE)**: FHE enables computation on encrypted data without decrypting it first. This allows secure outsourcing of sensitive computations to third-party clouds or machine learning services while keeping the data mathematically private.
  - **The TFHE Breakthrough**: Dr. Chillotti is a co-inventor of **TFHE** (Fast Fully Homomorphic Encryption over the Torus). Before TFHE, the "bootstrapping" process (a necessary noise-clearing step during homomorphic operations) took seconds to minutes per gate. TFHE slashed this to **under 0.1 seconds**, laying the foundation for practical, real-time homomorphic evaluation of Boolean circuits.
  - **Programmable Bootstrapping**: Her more recent work enables executing look-up tables homomorphically during the bootstrapping step, allowing non-linear operations (like activation functions in neural networks) to be performed efficiently on encrypted inputs.
- **Highlights & Sections**:
  - **Research & Publications**: Key papers on TFHE (specifically the CGGI scheme), homomorphic floating-point arithmetic, and secure k-nearest neighbors.
  - **Talks & Keynotes**: Practical tutorials, deep-dives, and slide decks explaining the mathematical foundations of TFHE.
  - **Teaching & Code**: Academic resources and references to tools like `TFHE-rs` (Zama's Rust library implementing TFHE).
- **Date Added**: 2026-08-25

---

## Research Activity Mimicking Framework
*Inspired by Ilaria Chillotti’s career structure, mapped for a PhD in Microelectronics / Integrated Circuit Design:*

### 1. Publications & Thesis (Core Contributions)
*   **Her Activity**: Peer-reviewed publications in top cryptology venues (Asiacrypt, CCS) and a highly focused PhD thesis on FHE and secure cloud computing.
*   **Mimic Plan**: 
    *   Target top-tier solid-state circuits conferences (ISSCC, VLSI Symposium, ESSCIRC) and IEEE journals (JSSC, TCAS).
    *   Synthesize research early into drafts and term papers during the first years of the PhD.

### 2. Talks, Panels & Summer Schools (Visibility & Dissemination)
*   **Her Activity**: Invited seminars, panels (e.g., CNCC, Decrypting Diversity), and lectures at international cryptography schools.
*   **Mimic Plan**:
    *   Present in lab seminars, PhD forums, and local workshops.
    *   Apply for student speaking opportunities at IEEE events (e.g., ISSCC Student Previews).
    *   Attend specialized international summer/winter schools (e.g., EPFL advanced engineering courses, CERN schools) to network and present posters.

### 3. Deep Dives & Blogposts (Outreach & Education)
*   **Her Activity**: Multi-part technical blog posts explaining TFHE internals, parameter selection, and key switching for developers and the broader research community.
*   **Mimic Plan**:
    *   Start a personal technical blog or write on platforms like Medium/Substack.
    *   Write tutorials explaining complex microelectronic topics, EDA tool flows (e.g., Cadence/Synopsys setup tricks), or simplified summaries of landmark papers. This builds a strong online presence and clarifies your own understanding.

### 4. Committees & Service (Academic Citizenship)
*   **Her Activity**: Serving on conference Program Committees (PCs), organizing workshops, and review panels.
*   **Mimic Plan**:
    *   Actively review papers for IEEE journals and circuits workshops as recommended by your advisor.
    *   Help organize local IEEE Solid-State Circuits Society (SSCS) student chapters, university seminars, or workshops.

### 5. Open-Source Repositories (Impact & Reproducibility)
*   **Her Activity**: Maintaining an active GitHub profile and contributing to open-source FHE tools (like `TFHE-rs` at Zama).
*   **Mimic Plan**:
    *   Upload helper scripts, layout generators (e.g., using Python/ALIGN), simulation setups, or open-source hardware designs (RISC-V components, custom cells) to GitHub.
    *   Support open-source silicon initiatives (like Tiny Tapeout, OpenLane/SkyWater PDK projects) to demonstrate hands-on design capability.
