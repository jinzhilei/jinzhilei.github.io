---
layout: page
permalink: /repositories/
title: repositories
description: Open-source code repositories for mathematical and computational models in biology and medicine.
nav: true
nav_order: 4
---

## GitHub Profile

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for user in site.data.repositories.github_users %}
    {% include repository/repo_user.liquid username=user %}
  {% endfor %}
</div>

---

## Code Repositories

<div style="display:grid;grid-template-columns:repeat(auto-fill,minmax(280px,1fr));gap:16px;margin-top:1rem;">
<a href="https://github.com/jinzhilei/QCIC-RCC" target="_blank" rel="noopener" style="text-decoration:none;color:inherit;">
  <div style="border:1px solid var(--global-divider-color, #e1e4e8);border-radius:8px;padding:16px;height:100%;display:flex;flex-direction:column;gap:8px;transition:box-shadow 0.2s;background:var(--global-bg-color, #fff);" onmouseover="this.style.boxShadow='0 4px 12px rgba(0,0,0,0.12)'" onmouseout="this.style.boxShadow='none'">
    <div style="display:flex;align-items:center;gap:8px;">
      <svg height="16" width="16" viewBox="0 0 16 16" fill="var(--global-text-color-light,#586069)"><path fill-rule="evenodd" d="M2 2.5A2.5 2.5 0 014.5 0h7A2.5 2.5 0 0114 2.5v10.042a.25.25 0 01-.4.2l-2.1-1.575-2.1 1.575a.25.25 0 01-.3 0L7 11.167l-2.1 1.575a.25.25 0 01-.4-.2V2.5zm2.5-1a1 1 0 00-1 1v8.91l1.6-1.2a.25.25 0 01.3 0L7.5 11.41l2.1-1.575a.25.25 0 01.3 0l1.6 1.2V2.5a1 1 0 00-1-1h-7z"/></svg>
      <span style="font-weight:600;font-size:14px;color:var(--global-theme-color,#0075b4);">QCIC-RCC</span>
    </div>
    <p style="font-size:12px;color:var(--global-text-color-light,#586069);flex-grow:1;margin:0;line-height:1.5;">A Quantitative Cancer-Immunity Cycle (QCIC) model integrating ODEs with stochastic modelling to characterize and predict tumour evolution in patients with advanced renal cell carcinoma.</p>
    <div style="display:flex;align-items:center;justify-content:space-between;margin-top:auto;">
      <span style="font-size:11px;"><span style="display:inline-block;width:12px;height:12px;border-radius:50%;background:#e16737;margin-right:5px;vertical-align:middle;"></span>MATLAB</span>
      <span style="font-size:11px;color:var(--global-text-color-light,#586069);background:var(--global-code-bg-color,#f6f8fa);padding:2px 8px;border-radius:12px;">Mathematical Oncology</span>
    </div>
  </div>
</a>
<a href="https://github.com/jinzhilei/DTP-Resistance" target="_blank" rel="noopener" style="text-decoration:none;color:inherit;">
  <div style="border:1px solid var(--global-divider-color, #e1e4e8);border-radius:8px;padding:16px;height:100%;display:flex;flex-direction:column;gap:8px;transition:box-shadow 0.2s;background:var(--global-bg-color, #fff);" onmouseover="this.style.boxShadow='0 4px 12px rgba(0,0,0,0.12)'" onmouseout="this.style.boxShadow='none'">
    <div style="display:flex;align-items:center;gap:8px;">
      <svg height="16" width="16" viewBox="0 0 16 16" fill="var(--global-text-color-light,#586069)"><path fill-rule="evenodd" d="M2 2.5A2.5 2.5 0 014.5 0h7A2.5 2.5 0 0114 2.5v10.042a.25.25 0 01-.4.2l-2.1-1.575-2.1 1.575a.25.25 0 01-.3 0L7 11.167l-2.1 1.575a.25.25 0 01-.4-.2V2.5zm2.5-1a1 1 0 00-1 1v8.91l1.6-1.2a.25.25 0 01.3 0L7.5 11.41l2.1-1.575a.25.25 0 01.3 0l1.6 1.2V2.5a1 1 0 00-1-1h-7z"/></svg>
      <span style="font-weight:600;font-size:14px;color:var(--global-theme-color,#0075b4);">DTP-Resistance</span>
    </div>
    <p style="font-size:12px;color:var(--global-text-color-light,#586069);flex-grow:1;margin:0;line-height:1.5;">A stochastic agent-based model (ABM) of solid tumour evolution coupling macroscopic population dynamics with microscopic epigenetic state inheritance during the cell cycle.</p>
    <div style="display:flex;align-items:center;justify-content:space-between;margin-top:auto;">
      <span style="font-size:11px;"><span style="display:inline-block;width:12px;height:12px;border-radius:50%;background:#f34b7d;margin-right:5px;vertical-align:middle;"></span>C++</span>
      <span style="font-size:11px;color:var(--global-text-color-light,#586069);background:var(--global-code-bg-color,#f6f8fa);padding:2px 8px;border-radius:12px;">Drug Resistance · ABM</span>
    </div>
  </div>
</a>
<a href="https://github.com/jinzhilei/CD19CAR-T" target="_blank" rel="noopener" style="text-decoration:none;color:inherit;">
  <div style="border:1px solid var(--global-divider-color, #e1e4e8);border-radius:8px;padding:16px;height:100%;display:flex;flex-direction:column;gap:8px;transition:box-shadow 0.2s;background:var(--global-bg-color, #fff);" onmouseover="this.style.boxShadow='0 4px 12px rgba(0,0,0,0.12)'" onmouseout="this.style.boxShadow='none'">
    <div style="display:flex;align-items:center;gap:8px;">
      <svg height="16" width="16" viewBox="0 0 16 16" fill="var(--global-text-color-light,#586069)"><path fill-rule="evenodd" d="M2 2.5A2.5 2.5 0 014.5 0h7A2.5 2.5 0 0114 2.5v10.042a.25.25 0 01-.4.2l-2.1-1.575-2.1 1.575a.25.25 0 01-.3 0L7 11.167l-2.1 1.575a.25.25 0 01-.4-.2V2.5zm2.5-1a1 1 0 00-1 1v8.91l1.6-1.2a.25.25 0 01.3 0L7.5 11.41l2.1-1.575a.25.25 0 01.3 0l1.6 1.2V2.5a1 1 0 00-1-1h-7z"/></svg>
      <span style="font-weight:600;font-size:14px;color:var(--global-theme-color,#0075b4);">CD19CAR-T</span>
    </div>
    <p style="font-size:12px;color:var(--global-text-color-light,#586069);flex-grow:1;margin:0;line-height:1.5;">Mathematical modelling of CD19-targeted CAR-T cell therapy dynamics, incorporating T cell exhaustion, antigen escape, and tumour-immune interactions via delay differential equations.</p>
    <div style="display:flex;align-items:center;justify-content:space-between;margin-top:auto;">
      <span style="font-size:11px;"><span style="display:inline-block;width:12px;height:12px;border-radius:50%;background:#f34b7d;margin-right:5px;vertical-align:middle;"></span>C++</span>
      <span style="font-size:11px;color:var(--global-text-color-light,#586069);background:var(--global-code-bg-color,#f6f8fa);padding:2px 8px;border-radius:12px;">Immunotherapy · DDE</span>
    </div>
  </div>
</a>
<a href="https://github.com/jinzhilei/ABM-Tumor-Immune-Dynamics" target="_blank" rel="noopener" style="text-decoration:none;color:inherit;">
  <div style="border:1px solid var(--global-divider-color, #e1e4e8);border-radius:8px;padding:16px;height:100%;display:flex;flex-direction:column;gap:8px;transition:box-shadow 0.2s;background:var(--global-bg-color, #fff);" onmouseover="this.style.boxShadow='0 4px 12px rgba(0,0,0,0.12)'" onmouseout="this.style.boxShadow='none'">
    <div style="display:flex;align-items:center;gap:8px;">
      <svg height="16" width="16" viewBox="0 0 16 16" fill="var(--global-text-color-light,#586069)"><path fill-rule="evenodd" d="M2 2.5A2.5 2.5 0 014.5 0h7A2.5 2.5 0 0114 2.5v10.042a.25.25 0 01-.4.2l-2.1-1.575-2.1 1.575a.25.25 0 01-.3 0L7 11.167l-2.1 1.575a.25.25 0 01-.4-.2V2.5zm2.5-1a1 1 0 00-1 1v8.91l1.6-1.2a.25.25 0 01.3 0L7.5 11.41l2.1-1.575a.25.25 0 01.3 0l1.6 1.2V2.5a1 1 0 00-1-1h-7z"/></svg>
      <span style="font-weight:600;font-size:14px;color:var(--global-theme-color,#0075b4);">ABM-Tumor-Immune-Dynamics</span>
    </div>
    <p style="font-size:12px;color:var(--global-text-color-light,#586069);flex-grow:1;margin:0;line-height:1.5;">Agent-based model simulating tumour-immune dynamics in the tumour microenvironment, capturing spatial heterogeneity and stochastic cell-cell interactions.</p>
    <div style="display:flex;align-items:center;justify-content:space-between;margin-top:auto;">
      <span style="font-size:11px;"><span style="display:inline-block;width:12px;height:12px;border-radius:50%;background:#f34b7d;margin-right:5px;vertical-align:middle;"></span>C++</span>
      <span style="font-size:11px;color:var(--global-text-color-light,#586069);background:var(--global-code-bg-color,#f6f8fa);padding:2px 8px;border-radius:12px;">Tumour Microenvironment</span>
    </div>
  </div>
</a>
<a href="https://github.com/jinzhilei/Optimal-adaptive-therapy" target="_blank" rel="noopener" style="text-decoration:none;color:inherit;">
  <div style="border:1px solid var(--global-divider-color, #e1e4e8);border-radius:8px;padding:16px;height:100%;display:flex;flex-direction:column;gap:8px;transition:box-shadow 0.2s;background:var(--global-bg-color, #fff);" onmouseover="this.style.boxShadow='0 4px 12px rgba(0,0,0,0.12)'" onmouseout="this.style.boxShadow='none'">
    <div style="display:flex;align-items:center;gap:8px;">
      <svg height="16" width="16" viewBox="0 0 16 16" fill="var(--global-text-color-light,#586069)"><path fill-rule="evenodd" d="M2 2.5A2.5 2.5 0 014.5 0h7A2.5 2.5 0 0114 2.5v10.042a.25.25 0 01-.4.2l-2.1-1.575-2.1 1.575a.25.25 0 01-.3 0L7 11.167l-2.1 1.575a.25.25 0 01-.4-.2V2.5zm2.5-1a1 1 0 00-1 1v8.91l1.6-1.2a.25.25 0 01.3 0L7.5 11.41l2.1-1.575a.25.25 0 01.3 0l1.6 1.2V2.5a1 1 0 00-1-1h-7z"/></svg>
      <span style="font-weight:600;font-size:14px;color:var(--global-theme-color,#0075b4);">Optimal-adaptive-therapy</span>
    </div>
    <p style="font-size:12px;color:var(--global-text-color-light,#586069);flex-grow:1;margin:0;line-height:1.5;">Optimal and adaptive therapy strategies for managing tumour heterogeneity and drug resistance, combining evolutionary game theory with optimal control.</p>
    <div style="display:flex;align-items:center;justify-content:space-between;margin-top:auto;">
      <span style="font-size:11px;"><span style="display:inline-block;width:12px;height:12px;border-radius:50%;background:#8b8b8b;margin-right:5px;vertical-align:middle;"></span>—</span>
      <span style="font-size:11px;color:var(--global-text-color-light,#586069);background:var(--global-code-bg-color,#f6f8fa);padding:2px 8px;border-radius:12px;">Optimal Control</span>
    </div>
  </div>
</a>
<a href="https://github.com/jinzhilei/CAR-T-Optimal" target="_blank" rel="noopener" style="text-decoration:none;color:inherit;">
  <div style="border:1px solid var(--global-divider-color, #e1e4e8);border-radius:8px;padding:16px;height:100%;display:flex;flex-direction:column;gap:8px;transition:box-shadow 0.2s;background:var(--global-bg-color, #fff);" onmouseover="this.style.boxShadow='0 4px 12px rgba(0,0,0,0.12)'" onmouseout="this.style.boxShadow='none'">
    <div style="display:flex;align-items:center;gap:8px;">
      <svg height="16" width="16" viewBox="0 0 16 16" fill="var(--global-text-color-light,#586069)"><path fill-rule="evenodd" d="M2 2.5A2.5 2.5 0 014.5 0h7A2.5 2.5 0 0114 2.5v10.042a.25.25 0 01-.4.2l-2.1-1.575-2.1 1.575a.25.25 0 01-.3 0L7 11.167l-2.1 1.575a.25.25 0 01-.4-.2V2.5zm2.5-1a1 1 0 00-1 1v8.91l1.6-1.2a.25.25 0 01.3 0L7.5 11.41l2.1-1.575a.25.25 0 01.3 0l1.6 1.2V2.5a1 1 0 00-1-1h-7z"/></svg>
      <span style="font-weight:600;font-size:14px;color:var(--global-theme-color,#0075b4);">CAR-T-Optimal</span>
    </div>
    <p style="font-size:12px;color:var(--global-text-color-light,#586069);flex-grow:1;margin:0;line-height:1.5;">Optimal control framework for CAR-T cell therapy dosing schedules, balancing anti-tumour efficacy and toxicity using Pontryagin's maximum principle.</p>
    <div style="display:flex;align-items:center;justify-content:space-between;margin-top:auto;">
      <span style="font-size:11px;"><span style="display:inline-block;width:12px;height:12px;border-radius:50%;background:#e16737;margin-right:5px;vertical-align:middle;"></span>MATLAB</span>
      <span style="font-size:11px;color:var(--global-text-color-light,#586069);background:var(--global-code-bg-color,#f6f8fa);padding:2px 8px;border-radius:12px;">Optimal Control · Immunotherapy</span>
    </div>
  </div>
</a>
<a href="https://github.com/jinzhilei/QCIC-Model" target="_blank" rel="noopener" style="text-decoration:none;color:inherit;">
  <div style="border:1px solid var(--global-divider-color, #e1e4e8);border-radius:8px;padding:16px;height:100%;display:flex;flex-direction:column;gap:8px;transition:box-shadow 0.2s;background:var(--global-bg-color, #fff);" onmouseover="this.style.boxShadow='0 4px 12px rgba(0,0,0,0.12)'" onmouseout="this.style.boxShadow='none'">
    <div style="display:flex;align-items:center;gap:8px;">
      <svg height="16" width="16" viewBox="0 0 16 16" fill="var(--global-text-color-light,#586069)"><path fill-rule="evenodd" d="M2 2.5A2.5 2.5 0 014.5 0h7A2.5 2.5 0 0114 2.5v10.042a.25.25 0 01-.4.2l-2.1-1.575-2.1 1.575a.25.25 0 01-.3 0L7 11.167l-2.1 1.575a.25.25 0 01-.4-.2V2.5zm2.5-1a1 1 0 00-1 1v8.91l1.6-1.2a.25.25 0 01.3 0L7.5 11.41l2.1-1.575a.25.25 0 01.3 0l1.6 1.2V2.5a1 1 0 00-1-1h-7z"/></svg>
      <span style="font-weight:600;font-size:14px;color:var(--global-theme-color,#0075b4);">QCIC-Model</span>
    </div>
    <p style="font-size:12px;color:var(--global-text-color-light,#586069);flex-grow:1;margin:0;line-height:1.5;">Core implementation of the Quantitative Cancer-Immunity Cycle (QCIC) model for analysing tumour-immune equilibrium and response to immunotherapy.</p>
    <div style="display:flex;align-items:center;justify-content:space-between;margin-top:auto;">
      <span style="font-size:11px;"><span style="display:inline-block;width:12px;height:12px;border-radius:50%;background:#e16737;margin-right:5px;vertical-align:middle;"></span>MATLAB</span>
      <span style="font-size:11px;color:var(--global-text-color-light,#586069);background:var(--global-code-bg-color,#f6f8fa);padding:2px 8px;border-radius:12px;">Cancer Immunity Cycle</span>
    </div>
  </div>
</a>
<a href="https://github.com/jinzhilei/Cellular_Automata_TME" target="_blank" rel="noopener" style="text-decoration:none;color:inherit;">
  <div style="border:1px solid var(--global-divider-color, #e1e4e8);border-radius:8px;padding:16px;height:100%;display:flex;flex-direction:column;gap:8px;transition:box-shadow 0.2s;background:var(--global-bg-color, #fff);" onmouseover="this.style.boxShadow='0 4px 12px rgba(0,0,0,0.12)'" onmouseout="this.style.boxShadow='none'">
    <div style="display:flex;align-items:center;gap:8px;">
      <svg height="16" width="16" viewBox="0 0 16 16" fill="var(--global-text-color-light,#586069)"><path fill-rule="evenodd" d="M2 2.5A2.5 2.5 0 014.5 0h7A2.5 2.5 0 0114 2.5v10.042a.25.25 0 01-.4.2l-2.1-1.575-2.1 1.575a.25.25 0 01-.3 0L7 11.167l-2.1 1.575a.25.25 0 01-.4-.2V2.5zm2.5-1a1 1 0 00-1 1v8.91l1.6-1.2a.25.25 0 01.3 0L7.5 11.41l2.1-1.575a.25.25 0 01.3 0l1.6 1.2V2.5a1 1 0 00-1-1h-7z"/></svg>
      <span style="font-weight:600;font-size:14px;color:var(--global-theme-color,#0075b4);">Cellular_Automata_TME</span>
    </div>
    <p style="font-size:12px;color:var(--global-text-color-light,#586069);flex-grow:1;margin:0;line-height:1.5;">Cellular automaton model of the tumour microenvironment (TME) to study spatiotemporal evolution of cancer cell populations under immune pressure and therapy.</p>
    <div style="display:flex;align-items:center;justify-content:space-between;margin-top:auto;">
      <span style="font-size:11px;"><span style="display:inline-block;width:12px;height:12px;border-radius:50%;background:#3572A5;margin-right:5px;vertical-align:middle;"></span>Python</span>
      <span style="font-size:11px;color:var(--global-text-color-light,#586069);background:var(--global-code-bg-color,#f6f8fa);padding:2px 8px;border-radius:12px;">Spatial Modelling</span>
    </div>
  </div>
</a>
<a href="https://github.com/jinzhilei/TcellExhaustion" target="_blank" rel="noopener" style="text-decoration:none;color:inherit;">
  <div style="border:1px solid var(--global-divider-color, #e1e4e8);border-radius:8px;padding:16px;height:100%;display:flex;flex-direction:column;gap:8px;transition:box-shadow 0.2s;background:var(--global-bg-color, #fff);" onmouseover="this.style.boxShadow='0 4px 12px rgba(0,0,0,0.12)'" onmouseout="this.style.boxShadow='none'">
    <div style="display:flex;align-items:center;gap:8px;">
      <svg height="16" width="16" viewBox="0 0 16 16" fill="var(--global-text-color-light,#586069)"><path fill-rule="evenodd" d="M2 2.5A2.5 2.5 0 014.5 0h7A2.5 2.5 0 0114 2.5v10.042a.25.25 0 01-.4.2l-2.1-1.575-2.1 1.575a.25.25 0 01-.3 0L7 11.167l-2.1 1.575a.25.25 0 01-.4-.2V2.5zm2.5-1a1 1 0 00-1 1v8.91l1.6-1.2a.25.25 0 01.3 0L7.5 11.41l2.1-1.575a.25.25 0 01.3 0l1.6 1.2V2.5a1 1 0 00-1-1h-7z"/></svg>
      <span style="font-weight:600;font-size:14px;color:var(--global-theme-color,#0075b4);">TcellExhaustion</span>
    </div>
    <p style="font-size:12px;color:var(--global-text-color-light,#586069);flex-grow:1;margin:0;line-height:1.5;">Dynamical systems model of T cell exhaustion in chronic infection and cancer, exploring epigenetic state transitions and reinvigoration strategies.</p>
    <div style="display:flex;align-items:center;justify-content:space-between;margin-top:auto;">
      <span style="font-size:11px;"><span style="display:inline-block;width:12px;height:12px;border-radius:50%;background:#8b8b8b;margin-right:5px;vertical-align:middle;"></span>—</span>
      <span style="font-size:11px;color:var(--global-text-color-light,#586069);background:var(--global-code-bg-color,#f6f8fa);padding:2px 8px;border-radius:12px;">T Cell Biology</span>
    </div>
  </div>
</a>
<a href="https://github.com/jinzhilei/Cell-type-transition" target="_blank" rel="noopener" style="text-decoration:none;color:inherit;">
  <div style="border:1px solid var(--global-divider-color, #e1e4e8);border-radius:8px;padding:16px;height:100%;display:flex;flex-direction:column;gap:8px;transition:box-shadow 0.2s;background:var(--global-bg-color, #fff);" onmouseover="this.style.boxShadow='0 4px 12px rgba(0,0,0,0.12)'" onmouseout="this.style.boxShadow='none'">
    <div style="display:flex;align-items:center;gap:8px;">
      <svg height="16" width="16" viewBox="0 0 16 16" fill="var(--global-text-color-light,#586069)"><path fill-rule="evenodd" d="M2 2.5A2.5 2.5 0 014.5 0h7A2.5 2.5 0 0114 2.5v10.042a.25.25 0 01-.4.2l-2.1-1.575-2.1 1.575a.25.25 0 01-.3 0L7 11.167l-2.1 1.575a.25.25 0 01-.4-.2V2.5zm2.5-1a1 1 0 00-1 1v8.91l1.6-1.2a.25.25 0 01.3 0L7.5 11.41l2.1-1.575a.25.25 0 01.3 0l1.6 1.2V2.5a1 1 0 00-1-1h-7z"/></svg>
      <span style="font-weight:600;font-size:14px;color:var(--global-theme-color,#0075b4);">Cell-type-transition</span>
    </div>
    <p style="font-size:12px;color:var(--global-text-color-light,#586069);flex-grow:1;margin:0;line-height:1.5;">Code repository (C++ and MATLAB) for the paper "Dynamics of cell type transition mediated by epigenetic modifications", modelling stochastic cell-fate switching.</p>
    <div style="display:flex;align-items:center;justify-content:space-between;margin-top:auto;">
      <span style="font-size:11px;"><span style="display:inline-block;width:12px;height:12px;border-radius:50%;background:#e16737;margin-right:5px;vertical-align:middle;"></span>MATLAB</span>
      <span style="font-size:11px;color:var(--global-text-color-light,#586069);background:var(--global-code-bg-color,#f6f8fa);padding:2px 8px;border-radius:12px;">Epigenetics · Cell Fate</span>
    </div>
  </div>
</a>
<a href="https://github.com/jinzhilei/scNMFME" target="_blank" rel="noopener" style="text-decoration:none;color:inherit;">
  <div style="border:1px solid var(--global-divider-color, #e1e4e8);border-radius:8px;padding:16px;height:100%;display:flex;flex-direction:column;gap:8px;transition:box-shadow 0.2s;background:var(--global-bg-color, #fff);" onmouseover="this.style.boxShadow='0 4px 12px rgba(0,0,0,0.12)'" onmouseout="this.style.boxShadow='none'">
    <div style="display:flex;align-items:center;gap:8px;">
      <svg height="16" width="16" viewBox="0 0 16 16" fill="var(--global-text-color-light,#586069)"><path fill-rule="evenodd" d="M2 2.5A2.5 2.5 0 014.5 0h7A2.5 2.5 0 0114 2.5v10.042a.25.25 0 01-.4.2l-2.1-1.575-2.1 1.575a.25.25 0 01-.3 0L7 11.167l-2.1 1.575a.25.25 0 01-.4-.2V2.5zm2.5-1a1 1 0 00-1 1v8.91l1.6-1.2a.25.25 0 01.3 0L7.5 11.41l2.1-1.575a.25.25 0 01.3 0l1.6 1.2V2.5a1 1 0 00-1-1h-7z"/></svg>
      <span style="font-weight:600;font-size:14px;color:var(--global-theme-color,#0075b4);">scNMFME</span>
    </div>
    <p style="font-size:12px;color:var(--global-text-color-light,#586069);flex-grow:1;margin:0;line-height:1.5;">A non-negative matrix factorisation framework (scNMFME) for quantifying immunosenescence from single-cell RNA-seq data.</p>
    <div style="display:flex;align-items:center;justify-content:space-between;margin-top:auto;">
      <span style="font-size:11px;"><span style="display:inline-block;width:12px;height:12px;border-radius:50%;background:#198CE7;margin-right:5px;vertical-align:middle;"></span>R</span>
      <span style="font-size:11px;color:var(--global-text-color-light,#586069);background:var(--global-code-bg-color,#f6f8fa);padding:2px 8px;border-radius:12px;">Single-cell Genomics</span>
    </div>
  </div>
</a>
</div>
