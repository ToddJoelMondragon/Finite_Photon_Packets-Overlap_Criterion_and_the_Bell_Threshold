# Finite Photon Packets, Overlap Criterion, and the Bell Threshold

[![arXiv](https://img.shields.io/badge/arXiv-XXXX.XXXXX-b31b1b.svg)](https://arxiv.org/abs/XXXX.XXXXX)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.XXXXXXX.svg)](https://doi.org/10.5281/zenodo.XXXXXXX)
[![ORCID](https://img.shields.io/badge/ORCID-0009-0004-7868-3021-A6CE39.svg)](https://orcid.org/0009-0004-7868-3021)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-blue.svg)](https://creativecommons.org/licenses/by/4.0/)

<blockquote>
  <strong>TL;DR</strong><br>
  Emission takes time → photons are finite spatiotemporal packets.
  Bell violations <strong>vanish</strong> (no post-selection, count no-clicks)
  when analyzer separation exceeds packet length: <strong>L &gtrsim; &ell;</strong>.
</blockquote>

<hr>

<h2 id="abstract">Abstract (1-paragraph)</h2>
<p>
  We define the photon packet length &ell; &equiv; c&nbsp;&tau;<sub>emit</sub>&nbsp;&kappa; and show that in
  loophole-free Bell tests evaluated with CH/CH&ndash;Eberhard (no post-selection, no-clicks counted),
  violations disappear once analyzer separation exceeds the packet length, L &gtrsim; &ell;.
  The same overlap criterion explains laser coherence build-up and imposes a gate-depth ceiling
  for photonic quantum circuits: &Sigma;&Delta;T &ll; &tau;<sub>emit</sub>.
  We outline compact, falsifiable bench experiments that vary &ell; by switching source linewidths
  (unseeded/seeded Nd:YAG, single-frequency CW) while keeping geometry fixed.
</p>

<h2 id="key-claims">Key claims</h2>
<ul>
  <li><strong>Finite packets:</strong> &ell; = c&nbsp;&tau;<sub>emit</sub>&nbsp;&kappa; with &kappa; = O(1) (lineshape).</li>
  <li><strong>Visibility from first-order coherence:</strong> V(&Delta;L) &approx; | g<sup>(1)</sup>(&Delta;L / c) |
      (Lorentzian &rArr; V &approx; e<sup>&minus;|&Delta;L|/&ell;</sup>).</li>
  <li><strong>Bell threshold:</strong> S(L) &approx; 2 + &alpha; V(L) for L &lesssim; &ell;;
      and S(L) &rarr; 2 when L &gtrsim; &ell; (CH/CH&ndash;Eberhard; no post-selection).</li>
  <li><strong>QC cliff:</strong> &Sigma;&Delta;T &ll; &tau;<sub>emit</sub>.</li>
</ul>

<hr>

<h2 id="contents">Repository contents</h2>
<pre><code>/final_finite_photon_paper_cleaned.pdf   # Camera-ready manuscript (as on arXiv/RG/Academia)
CITATION.cff                             # Preferred citation (arXiv / DOI once assigned)
LICENSE                                  # CC BY 4.0 (or your choice)
README.md                                # This file (HTML embedded)
</code></pre>

<h2 id="build">Build (optional, if you ship LaTeX)</h2>
<pre><code class="language-bash"># Requires TeX Live with REVTeX4-2
latexmk -pdf main.tex
# Expect a clean run: no ?? references; no catastrophic overfull boxes.
</code></pre>

<hr>

<h2 id="bench-tests">Falsifiable bench tests (one-pager for experimentalists)</h2>
<ul>
  <li><strong>Bell vs. packet length:</strong> Fix geometry and analyzers; swap sources to vary &ell;:
    (i) unseeded Q-switched (short &ell;), (ii) injection-seeded (longer &ell;),
    (iii) single-frequency CW (very long &ell;).
    Evaluate with <strong>CH/CH&ndash;Eberhard</strong>, include no-clicks, forbid post-selection.
    <em>Prediction:</em> violations only for L &lesssim; &ell;.</li>
  <li><strong>HOM ruler:</strong> Two identical packets on 50/50 BS.
    Dip/visibility vs delay follows V(&Delta;L).</li>
  <li><strong>Gate-depth cliff:</strong> Mach&ndash;Zehnder with Pockels phase gate;
    fidelity collapses when &Sigma;&Delta;T &approx; &tau;<sub>emit</sub>; shifts with &ell;.</li>
</ul>

<p><em>Safeguards:</em> pre-register trials; publish full time tags; fixed coincidence windows; spacelike-separated RNGs/settings.</p>

<hr>

<h2 id="cite">Cite</h2>
<p>See <a href="./CITATION.cff">CITATION.cff</a> for auto-generated BibTeX via GitHub&rsquo;s &ldquo;Cite this repository&rdquo; button.</p>

<p><strong>Preprint (preferred)</strong></p>
<pre><code class="language-bibtex">@article{Mondragon2025FinitePackets,
  title   = {Finite Photon Packets, Overlap Criterion, and the Bell Threshold},
  author  = {Mondragon, Todd Joel},
  journal = {arXiv},
  year    = {2025},
  eprint  = {ARXIV_ID},
  url     = {https://arxiv.org/abs/ARXIV_ID}
}
</code></pre>

<p><strong>Software/Data DOI (optional, when Zenodo is connected)</strong></p>
<pre><code class="language-bibtex">@misc{Mondragon2025Repo,
  title  = {Finite Photon Packets, Overlap Criterion, and the Bell Threshold (Repository)},
  author = {Mondragon, Todd Joel},
  year   = {2025},
  doi    = {10.5281/zenodo.ZENODO_DOI},
  url    = {https://doi.org/10.5281/zenodo.ZENODO_DOI}
}
</code></pre>

<hr>

<h2 id="links">Links</h2>
<ul>
  <li><strong>arXiv:</strong> <a href="https://arxiv.org/abs/ARXIV_ID">https://arxiv.org/abs/ARXIV_ID</a></li>
  <li><strong>DOI (Zenodo):</strong> <a href="https://doi.org/10.5281/zenodo.ZENODO_DOI">https://doi.org/10.5281/zenodo.ZENODO_DOI</a></li>
  <li><strong>ORCID:</strong> <a href="https://orcid.org/0009-0004-7868-3021">https://orcid.org/0009-0004-7868-3021</a></li>
  <li><strong>Repository:</strong> <a href="REPO_URL">REPO_URL</a></li>
</ul>

<hr>

## Licensing

**PDF/Text (paper):**  
*Finite Photon Packets, Overlap Criterion, and the Bell Threshold* © 2025 Todd Joel Mondragon is licensed under the **Creative Commons Attribution 4.0 International (CC BY 4.0)**.  
See [`LICENSE-CC-BY-4.0`](./LICENSE-CC-BY-4.0) or <https://creativecommons.org/licenses/by/4.0/>.

**Code:**  
Released under the **MIT License**. See [`LICENSE-MIT`](./LICENSE-MIT).

> Unless otherwise noted: `/paper/**` is CC BY 4.0, `/code/**` is MIT. Third-party content keeps its original license.
<hr>

<h2 id="ack">Acknowledgments</h2>
<p>
  The author used digital tools (ChatGPT, Claude, ScholarAI, Wolfram) for editorial feedback,
  citation management, and consistency checks.
  All conceptual work, theoretical modeling, and scientific interpretation are the author’s original contributions.
</p>
