# Oxygenation 16-Patient Floor Simulation

A standalone interactive nursing-school simulation for the oxygenation unit.

## What changed

The game now opens as a **0700 16-patient nursing assignment** instead of a traditional quiz menu. You choose rooms, follow handoff data, answer one question at a time, and revisit patients as their conditions evolve.

## Core features

- 16-room floor board
- Evolving patient conditions and timed updates
- Hidden diagnoses when recognition from cues is part of the learning goal
- Single-best-answer NCLEX questions
- SATA
- Ordered response
- CJMM through **Evaluate Outcomes**
- Competing multi-patient priority questions
- RN/LVN-LPN/UAP delegation
- Medication questions embedded in patient scenarios
- ABG → intervention questions
- Pathophysiology-based rationales
- SBAR practice
- Missed-question review
- Weak-topic tracking
- Per-room and overall progress
- Randomized answer positions for MC/SATA
- 25-question advanced end-of-shift challenge
- `localStorage` progress saving

## Floor topics

The 16 patients distribute the unit across:

- Pneumonia
- Pneumonia complications
- COPD
- Asthma
- Cystic fibrosis
- Pulmonary embolism
- Anticoagulation
- Sarcoidosis
- Atelectasis
- Tracheobronchitis
- Pleural effusion
- Thoracentesis
- Chest-tube care
- ABG/respiratory assessment

Some disease processes appear in more than one room from different angles.

## Priority framework

Difficult priority rationales use:

1. Is there an immediate ABC threat?
2. Is the finding acute/new/unexpected?
3. Is there evidence of deterioration?
4. Is this an actual problem or only a risk?
5. Which patient is most likely to suffer harm if care is delayed?
6. What can safely wait?

## Medication emphasis

The medication roster retains the oxygenation medication-sheet content, including albuterol, tiotropium, guaifenesin, dextromethorphan, N-acetylcysteine, budesonide, methylprednisolone, fluticasone/salmeterol, formoterol, pancrelipase, montelukast, dornase alfa, heparin, enoxaparin, warfarin, and apixaban.

For apixaban, this version uses **andexanet alfa** as the specific reversal agent.

## Running locally

1. Download `Oxygenation_16_Patient_Floor_Simulation.html`.
2. Open it in a modern browser.
3. Start from the 0700 floor board.

No server or build process is required.

## GitHub Pages

1. Create a repository.
2. Upload `Oxygenation_16_Patient_Floor_Simulation.html`.
3. Rename it to `index.html` if you want it to launch from the Pages root.
4. Add this `README.md`.
5. Go to **Settings → Pages**.
6. Choose **Deploy from a branch** and select the main branch/root.

## Study flow

**What disease is this? → Why is this happening? → What should I monitor? → What treatment will help? → What could go wrong? → What do I do first? → Can I delegate this? → Did my intervention work?**

This project is for nursing-school study and does not replace current clinical policy, drug references, provider orders, or professional judgment.
