# VYOMCUT MOTION · Demonstration benchmark

**Assessment date:** 23 September 2026  
**Evaluation unit:** One completed, publicly shared *edited trailer* — [VYOMCUT business demonstration](media/VYOMCUT_BUSINESS_DEMO.mp4).  
**Purpose:** Document what the published video demonstrates and place it alongside the *advertised capabilities* of selected commercial video-generation services.

> **Important:** This is a **demonstration audit and capability comparison, not a head-to-head quality benchmark**. No competitor videos were generated with the same prompt, references, hardware, editing rules, or evaluation protocol. VYOMCUT is showcased here as an end-to-end production presentation, while the named services below primarily advertise video-generation capabilities. These are different evaluation units.

## 1. What the public demonstration achieves

The following properties were measured from the submitted `VYOMCUT_BUSINESS_DEMO.mp4` using FFprobe. They describe the **final exported file**, not its source-shot generation resolution or an underlying service's native output limits.

| Measured property | Verified demo result |
| :-- | :-- |
| Public deliverable | Edited trailer-format MP4 with visual presentation and an audio track |
| Total runtime | **7.542 seconds** |
| Export frame size | **1280 × 720 (720p)** |
| Frame rate | **24 frames per second** |
| Video stream | **H.264**, 181 frames |
| Audio stream | **AAC stereo**, 44.1 kHz |
| Published file size | **873,616 bytes** (approximately 0.83 MiB) |
| Number of assessed outputs | **1** |

**Interpretation:** The completed showcase demonstrates that one short video with a branded presentation and an encoded audio/video deliverable was exported. The presence of an audio stream does **not**, by itself, validate synchronized sound quality, speech intelligibility, or that audio was generated natively with the moving scene.

### Not established by this demonstration

- Quality against other video-generation services; story adherence; character consistency; motion realism; temporal stability; independent audience preference.
- Native source-shot resolution and native single-shot duration (the numbers above refer to an **edited export**).
- Generation throughput, elapsed per-shot time, GPU utilisation, service pricing, cost per finished minute, success rate, or consistent results across multiple runs.
- Any model-independent visual-quality score, industry certification, market share, or quality ranking.

## 2. Published capability context — not a scorecard

The following are **vendor-reported product specifications** current at the assessment date. They are not measurements made on VYOMCUT's test setup and should not be read as comparable achievement scores.

| Product or showcase | Unit described | Video duration | Resolution information | Audio information |
| :-- | :-- | :-- | :-- | :-- |
| **VYOMCUT MOTION public demo** | Finished, edited trailer export | **7.542 s observed** | **1280×720 observed final export**; native shot resolution unmeasured | **AAC stereo track present**; native audiovisual-generation capability unmeasured |
| [**Seedance 2.0**](https://seed.bytedance.com/en/blog/seedance-2-0-official-launch) | Vendor-advertised model output | **Up to 15 s** of multi-shot content (vendor statement) | Not assessed from the cited launch note | Vendor describes jointly generated audio and video |
| [**Runway Gen-4.5**](https://help.runwayml.com/hc/en-us/articles/46974685288467-Creating-with-Gen-4-5) | Vendor-documented single generation | **2–10 s** | **720p** per listed settings | Native audiovisual generation not established by the cited Gen-4.5 specifications |
| [**Google Veo 3.1**](https://ai.google.dev/gemini-api/docs/veo) | Vendor-documented single generation via Gemini API | **4, 6 or 8 s** | **720p, 1080p, or 4K**, with mode- and duration-dependent restrictions | Vendor documents native audio with video |
| [**Kling VIDEO 3.0**](https://ir.kuaishou.com/news-releases/news-release-details/kling-ai-launches-30-model-ushering-era-where-everyone-can-be) | Vendor-advertised model output | **Up to 15 s** | Not assessed from the cited release | Vendor advertises native audio generation |

**Do not infer:** Because a finished edited trailer is 7.542 seconds or 720p, that does not establish whether its underlying shot generator is more or less capable than a vendor's single-shot generator. Video and audio stream presence does not establish the same kind of native joint audio-video generation claimed by some vendors. No model-quality, cost, speed, fidelity, or prompt-following winner is determined here.

**Source notes:** Seedance, Runway, Google, and Kling entries above link directly to their respective primary vendor documentation or launch announcement. Product features, access, specifications and pricing can change; recheck vendor documentation before making purchase or production decisions.

## 3. Proposed reproducible comparison protocol

To publish meaningful future comparisons against Seedance, Runway, Veo, or Kling, run *each* system on the same **five pre-registered creative briefs** (for example: landscape walk, character close-up, product turntable, two-character interaction, and controlled camera move).

1. Hold the input text, approved reference image (where supported), target aspect ratio, target duration, delivery audio requirements, and maximum number of attempts constant or document exceptions.
2. Preserve every raw single-shot output alongside the *separately edited* final trailer, without upscaling or post-processing when evaluating native generation quality.
3. Record wall-clock generation time, compute or credits consumed, attempts, errors, native shot duration, and source/output resolution. Compare costs only on the same priced workload and currency/date.
4. Have independent reviewers evaluate randomized, anonymized clips for prompt adherence, motion naturalness, temporal consistency, character continuity, audio alignment, and suitability for the brief. Report the rubric, reviewer count, score distributions, and uncertainty.
5. Publish the prompts, settings, raw outputs or verifiable output links, and per-system limitations before drawing comparative conclusions.

Until a matched test is conducted, the verified achievement remains **one complete 7.542-second 720p/24-fps edited demonstration with an AAC stereo track**, not a measured quality comparison.

---

*VYOMCUT MOTION is a portfolio/showcase identity, not presented here as a registered brand. Production source, private client materials and internal model details are intentionally not published.*
