![SeaTulane hero mockup showing the booking dashboard](/images/portfolio/seatulane/seatulane-banner.jpeg)

## SeaTulane at a Glance

SeaTulane is a collaborative seat-booking prototype that helps Tulane students locate, reserve, and manage study spaces across Howard-Tilton Memorial Library. The system brings live capacity tracking, interactive floor maps, and booking controls into one experience so students can stop guessing whether a seat will be available before they arrive.

<div style="margin:24px 0;">
  <a href="{{ page.figma_link }}" class="btn btn--primary" target="_blank" rel="noopener">
    Explore the Interactive Prototype
  </a>
</div>

## Motivation & Research

- **Crowding and wasted trips:** 8 in-depth interviews revealed recurring stories of students circling floors or texting friends to verify availability before commuting to campus.
- **Need for transparency:** A survey of 27 students showed strong demand for a capacity tracker that surfaces real-time seat counts by floor and clarifies noise levels.
- **Accountability & fairness:** Participants wanted a way to release unused seats quickly and to prevent double-booking, particularly during midterms when demand surges.

## Core Experience

- **Capacity tracker:** A live heatmap displays availability across floors, highlights crowding trends, and lets students filter by preferred amenities.
- **Seat reservation flow:** Students can inspect seat details, see status indicators, and reserve spots with guardrails that block already-claimed seats.
- **Booking management:** “My bookings” consolidates upcoming, past, and favorite seats with inline actions to edit or cancel reservations on the fly.
- **Notification preferences:** Learners opt into reminders and alerts so they never lose track of reservations or floor-wide changes.

<div style="display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:18px;">
  <figure style="margin:0;">
    <img src="/images/portfolio/seatulane/seatulane-home.png" alt="SeaTulane home screen summarizing current bookings" style="width:100%;border-radius:8px;" />
    <figcaption>Home dashboard surfaces upcoming reservations and quick links to core actions.</figcaption>
  </figure>
  <figure style="margin:0;">
    <img src="/images/portfolio/seatulane/seatulane-capacity.png" alt="SeaTulane capacity tracker highlighting available seats" style="width:100%;border-radius:8px;" />
    <figcaption>Capacity tracker shows seat status by floor and prompts a reserve action for open spots.</figcaption>
  </figure>
  <figure style="margin:0;">
    <img src="/images/portfolio/seatulane/seatulane-history.png" alt="SeaTulane booking history list" style="width:100%;border-radius:8px;" />
    <figcaption>Booking history organizes current, previous, and favorite seats with inline management controls.</figcaption>
  </figure>
  <figure style="margin:0;">
    <img src="/images/portfolio/seatulane/seatulane-settings.png" alt="SeaTulane notification settings toggles" style="width:100%;border-radius:8px;" />
    <figcaption>Notification settings let students fine-tune reminders, seat alerts, and system behaviors.</figcaption>
  </figure>
</div>

## Design Process

1. **Discovery:** Conducted interviews and surveys to map commuters’ routines, preferred study floors, and pain points when crowds peak.
2. **Modeling:** Synthesised insights into personas, journey maps, and scenarios that emphasised noise preferences, collaboration needs, and travel time.
3. **Prototyping:** Sketched seat maps, storyboards, and low-fidelity flows before building a high-fidelity Figma prototype with interactive overlays.
4. **Evaluation:** Ran heuristic reviews and user walkthroughs that exposed issues such as ambiguous booking labels and the need for prominent password reset paths—each addressed in the final iteration.

## Outcomes & Next Steps

- Clarified key actions (e.g., “Current Bookings”) and added confirmations around destructive actions to reduce misclicks observed during testing.
- Highlighted password recovery and introduced time limits on reservations to keep the system fair during peak weeks.
- Future work includes integrating real sensor feeds for capacity data and piloting with library staff to refine moderation and no-show policies.
