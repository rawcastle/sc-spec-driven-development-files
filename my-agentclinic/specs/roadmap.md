# AgentClinic Roadmap

Build in small vertical slices. Each phase should leave the application runnable and deliver one observable improvement to an agent or staff workflow.

1. **Application shell**: establish the Next.js TypeScript app, a shared layout, and agent/staff navigation.
2. **Ailment directory**: show a small set of sample ailments with clear descriptions and detail pages.
3. **Therapy directory**: list therapies and connect each therapy to the ailments it may address.
4. **Appointment request**: let an agent choose a therapy and submit an appointment request; show a clear confirmation.
5. **Staff appointment view**: give staff a dashboard to review incoming requests and their status.
6. **Scheduling actions**: let staff confirm or decline a request and show the updated status to the agent.
7. **Persistence**: save ailments, therapies, and appointment changes in durable storage, preserving the workflows above.
8. **Reliability and polish**: add focused workflow tests, handle empty and error states, and check accessibility and modern-browser behavior.

Keep each phase small enough to review and verify on its own. Do not start a later workflow before its prerequisite is usable; adjust the ordering only when implementation evidence shows a better path to a working agent-and-staff experience.