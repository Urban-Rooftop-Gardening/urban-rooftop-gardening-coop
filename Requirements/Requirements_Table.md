# Requirements Table

## Functional Requirements

| ID | Type | Description | Priority | Acceptance Criteria | Rationale |
|---|---|---|---|---|---|
| FR-001 | Functional | The system shall allow Co-op Gardeners to register rooftop plots by providing plot details such as location, size, and available growing area. | High | Pass: Valid plot details are successfully saved. Fail: The system accepts incomplete or invalid plot information. | Enables the co-op to maintain an organized record of registered rooftop plots. |
| FR-002 | Functional | The system shall allow Co-op Gardeners to log seasonal crop planting dates and calculate estimated harvest windows and expected yield weight. | High | Pass: A valid planting date generates an estimated harvest window and expected yield. Fail: Invalid planting date information is accepted. | Helps gardeners plan crop cultivation and harvesting activities. |
| FR-003 | Functional | The system shall allow Co-op Gardeners to record crop yields and harvest schedules for registered rooftop plots. | High | Pass: Valid harvest and yield information is saved and displayed correctly. Fail: Invalid harvest information is stored. | Helps gardeners track crop production and manage harvest activities. |
| FR-004 | Functional | The system shall allow Co-op Gardeners to share soil maintenance tips with the community. | Medium | Pass: A valid soil maintenance tip is successfully submitted and displayed. Fail: Empty or invalid tips are accepted. | Promotes knowledge sharing and improves community gardening practices. |
| FR-005 | Functional | The system shall allow Co-op Gardeners to list and trade surplus produce with other community members. | High | Pass: A valid surplus produce listing becomes available on the trade board. Fail: Invalid or unavailable produce is listed. | Helps reduce food wastage and supports community-based produce exchange. |

## Non-Functional Requirements

| ID | Type | Description | Priority | Acceptance Criteria | Rationale |
|---|---|---|---|---|---|
| NFR-001 | Performance | The produce trade board shall update available surplus listings in real time across community members. | High | Pass: Changes to surplus listings are reflected within the defined target latency under simulated peak load. Fail: Listings remain outdated beyond the target latency. | Ensures community members see current surplus produce availability. |
| NFR-002 | Security | The system shall ensure that only authenticated and authorized users can access protected user, plot, crop, and produce information. | High | Pass: Unauthorized users are prevented from accessing protected information. Fail: An unauthorized user can access restricted data or functions. | Protects community and user information from unauthorized access. |
