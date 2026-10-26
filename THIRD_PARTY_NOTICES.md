# Third-party notices

Spok Quntum (Copyright © 2026 Srdjan Stojkovic) is distributed under the GNU
General Public License v3.0 or later. It incorporates the following components.
Exact versions are listed in `third_party/VERSIONS.txt`; each component's
licence text is in its folder.

| Component | Used for | Copyright | Licence |
|---|---|---|---|
| sst-filters | Filter models 2–20 (all except Spok Ladder) | Surge Synth Team and contributors | GPL-3.0-or-later |
| sst-effects | Stereo delay and reverb | Surge Synth Team and contributors | GPL-3.0-or-later |
| sst-basic-blocks | DSP and SIMD helpers used by the above | Surge Synth Team and contributors | GPL-3.0-or-later |
| SIMDe 0.8.2 | SSE intrinsics on Apple Silicon | SIMD Everywhere contributors | MIT |
| fmt 12.1.0 | String formatting used by the above (header-only) | Victor Zverovich and contributors | MIT |
| JUCE 8 | Plug-in framework, GUI, VST3 wrapper | Raw Material Software Limited | AGPL-3.0 or commercial |
| VST3 SDK (inside JUCE) | VST3 plug-in format | Steinberg Media Technologies GmbH | as distributed with JUCE |

Some filter models in sst-filters are ports of earlier open-source designs; see
the source headers in `third_party/sst-filters/include` for the original
authors.

"VST" is a trademark of Steinberg Media Technologies GmbH. The EI Niš name
refers to the Serbian electronics manufacturer and is used only to describe
the inspiration for the tube saturation stage.
