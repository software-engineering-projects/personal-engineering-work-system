## 📊 ENGINEERING TASK TRACKER (JIRA-STYLE)

| ID | Title | Type | Status | Priority | Current Step | Done Criteria | Notes |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| BE-001 | Setup Deno Project | Setup | DONE | P1 | Completed | Project runs with deno run main.ts | Base project initialized |
| BE-002 | Create Order Module Structure | Feature | IN PROGRESS | P1 | Writing service logic | Module folder + files created | Following modular structure |
| BE-003 | Implement createOrder Function | Feature | TODO | P1 | Not started | Function returns valid order object | Depends on types |
| BE-004 | Add Type Definitions | Feature | TODO | P1 | Not started | Types enforce correct input | - |
| BE-005 | Add Runtime Validation | Enhancement | TODO | P2 | Not started | Invalid input throws error | |

```
STATUS DEFINITIONS (STRICT)
  • Use only these:
    • TODO → Not started
    • IN PROGRESS → Actively working
    • BLOCKED → Cannot proceed
    • REVIEW → Needs validation/testing
    • DONE → Fully completed (meets criteria)

CURRENT TASK FOCUS (YOUR DAILY DRIVER)
  • Current Task
    • ID: BE-002
    • Title: Create Order Module Structure
    • Goal: Set up modular folder structure for order module
    • Steps:
      • Create /modules/order/
      • Add order.types.ts
      • Add order.service.ts
      • Connect import to main.ts
    • Done Criteria:
      • Folder structure matches design
      • Files compile without error
      • Imports work correctly

NEXT TASK QUEUE (NO THINKING REQUIRED)
  • NEXT:
    • BE-003 → Implement createOrder function
    • BE-004 → Add type definitions
    • BE-005 → Add runtime validation
  • Rule:
    • When current task = DONE → immediately pull next task

PROGRESS LOG (VERY IMPORTANT)
  • Log Entry
    • Date: 2026-04-24
    • Task: BE-002
    • Progress:
      • Created module folder
      • Added base files
      • Started service function
    • Blockers:
      • None
    • Next Step:
      • Complete service logic

TASK BREAKDOWN FOR PROJECT
  • Setup Phase
    • BE-001 → Setup Deno project
    • BE-002 → Create modular folder structure
  • Core Feature
    • BE-003 → Implement createOrder
    • BE-004 → Define TypeScript types
    • BE-005 → Connect module to main.ts
  • Validation Layer
    • BE-006 → Add runtime validation function
    • BE-007 → Integrate validation into service
  • Testing / Verification
    • BE-008 → Test valid inputs
    • BE-009 → Test invalid inputs
  • Improvements
    • BE-010 → Refactor structure
    • BE-011 → Add logging

WORKFLOW RULES (CRITICAL)
  • Rule 1: One Task at a Time
    • Never work on multiple tasks simultaneously
  • Rule 2: Always Define “Done”
    • If no done criteria → task is invalid
  • Rule 3: No Memory-Based Work
    • Everything must be:
      • Logged
      • Tracked
      • Visible
  • Rule 4: Finish Before Switching
    • Do not abandon tasks mid-way unless BLOCKED
  • Rule 5: Update Tracker Before Stopping
    • Update status
    • Write next step

MINIMAL DAILY FLOW
  • Start of Day
    • Check tracker
    • Pick current task
    • Review steps
  • During Work
    • Execute only that task
    • Log blockers
  • End of Session
    • Update status
    • Write next step
    • Queue next task

MENTAL MODEL
  • You are training:
    • “I move tasks through a system with defined states”
  • Not:
    • “I just code until I feel done”

SIMPLE VERSION (OPTIONAL)
  • CURRENT:
    • BE-002 - Create module structure
  • NEXT:
    • BE-003 - createOrder function
    • BE-004 - types
  • DONE:
    • BE-001 - setup project

Final Insight
  • You are building:
    • structured developer workflow execution
  • Core expectations this trains:
    • clear task ownership
    • progress visibility
    • predictable execution
```
