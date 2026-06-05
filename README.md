# Virtual Exhibit Proposal: Multi-Core Processors: Solving the Power Wall Problem

## Group 8 Members
Name 
1. Colcol, Massimo
2. Dicreto, Eirnan  
3. Ong, Kyle 
4. Salvador, Miguel 
5. Tanchiao, Manuel

## Group’s Topic Theme
For decades, computer processors got faster simply by increasing their clock speed, the number
of operations they could perform per scond. However, around the mid-2000s, this approach hit a physical barrier known as the **"Power Wall"**. As clock speeds increased, processors generated unsustainable amounts of heart and consumed too much power. Cooling fans could no loonger keep up, and chops would 
throttle down or fail. This was a serious architectural problem: manufacturers could no longer make single cores faster without literally melting the silicon.

The solution came from changing the fundamental design of processors. Instead of pushing one core to impossible speeds, engineers at Intel, AMD, and IBM introduced **multi-core processors**, placing two or more independent cores on a single chip. These cores could work in parallel, handling multiple tasks at once. While each individual core ran at a moderate speed, the combined performance continued to grow. This solved the power wall because parallel processing produced far less heat than cranking up the frequency of a single core.

## Group’s Tech Stack Plan
- **Framework:** Astro 6
- **UI Library:** React (for interactive components)
- **Content:** MDX files (exhibit text, images, embedded components)
- **Language:** [fill this up depending on our proposed project idea]
- **Styling:** [fill this up depending on our proposed layout]
- **Interactive Element Implementation:** [fill this up depending on our proposed interactive element].
- **Version Control:** GitHub

## Proposed Interactive Element [Explanation only]
**Name:** The Thermal Architecture Simulator

**What it does:**  
A highly detailed interactive dashboard that allows visitors to step into the role of a computer architect. The interface challenges users to design a processor that maximizes performance without exceeding thermal and power limits (The Power Wall). It features a control panel for hardware configuration, a live CPU view and metrics, and a comprehensive performance and curation results section that evaluates the processor that they built.

**How the user interacts with it:**  
Users interact with a suite of configuration sliders in the control panel to set the power budget, clock speed, and core count. After configuring their chip, they click the test design button. They then analyze the resulting data: monitoring the temperature gauges, checking if their design passed the design analysis checklist, reviewing benchmark scores for specific workloads  and receiving a final letter grade for their creation.

**Technical implementation:**  
The designer will be built as a react functional component. A custom algorithmic function will calculate the derived states: Temperature, Power Usage, and the final Curation Rating based on the combination of clock speed and active cores. The component will feature dynamic rendering to physically generate the CPU view grid and conditionally render warning banners if the user's design overheats.

**How it teaches the topic:**  
Rather than simply reading about the Power Wall, users experience it mathematically and visually. If a user tries to achieve a high score by simply maxing out the clock speed slider on a single core, the telemetry will instantly show a thermal failure. To achieve a good curation rating and high performance scores, the user is forced to discover the historical solution themselves, lowering the clock speed and increasing the core count to maintain efficiency.

## Mobile-Responsive Layout [Picture w/ short explanation 3-5 sentences]
![alt text](public/image-1.png)

## Tentative Style Guide Snapshot [Picture only]
![alt text](public/image.png)