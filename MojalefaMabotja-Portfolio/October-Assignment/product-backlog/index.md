# PowerShare — Product Backlog

## 1. Introduction

The product backlog is a prioritised list of features and requirements for the PowerShare platform. PowerShare is a portable power station rental platform designed to help small businesses access portable power solutions when electricity is unavailable.

The backlog identifies the main features required by customers and administrators. It helps the team organise development work according to user needs and the purpose of the application.

## 2. Product Goal

The goal of PowerShare is to provide a platform where customers can explore available portable power stations, submit rental bookings, track booking progress, and access relevant account information. Administrators need to manage batteries, customers, bookings, and reports.

## 3. Product Backlog Items

| ID   | User Story                                                                                                    | Priority | Acceptance Criteria                                                                                                                                  | Status    |
| ---- | ------------------------------------------------------------------------------------------------------------- | -------- | ---------------------------------------------------------------------------------------------------------------------------------------------------- | --------- |
| PB01 | As a customer, I want to register an account so that I can access the platform.                               | High     | The customer can submit registration details; required fields are validated; successful registration provides appropriate feedback.                  | Completed |
| PB02 | As a customer, I want to log in so that I can securely access my account.                                     | High     | The customer can enter login credentials; invalid credentials are handled; successful login provides access to the account.                          | Completed |
| PB03 | As a customer, I want to browse available batteries so that I can find a suitable power solution.             | High     | Available batteries are displayed; relevant battery information is visible; rental prices are presented where configured.                            | Completed |
| PB04 | As a customer, I want to view battery details so that I can understand the product before renting it.         | High     | Battery details can be opened; relevant specifications and rental information are displayed; the customer can return to the previous view.           | Completed |
| PB05 | As a customer, I want to create a rental booking so that I can request a battery.                             | High     | The customer can submit a booking; the system processes the request; the booking status can be viewed.                                               | Completed |
| PB06 | As a customer, I want to view my bookings so that I can track my rental requests.                             | High     | The customer can access their bookings; booking information is displayed; booking statuses are visible.                                              | Completed |
| PB07 | As a customer, I want to make a payment so that I can follow the payment process for my rental.               | High     | A payment interface is available; the payment workflow provides feedback; the payment outcome is displayed according to the implemented workflow.    | Completed |
| PB08 | As a customer, I want to receive booking notifications so that I can stay informed about booking progress.    | Medium   | Booking-related updates can be presented; notification information is displayed clearly; relevant status changes are communicated where implemented. | Completed |
| PB09 | As a customer, I want to manage my profile so that my account information remains up to date.                 | Medium   | Profile information can be viewed; supported fields can be updated; the system provides feedback after an update.                                    | Completed |
| PB10 | As an administrator, I want to manage batteries so that the platform's battery information can be maintained. | High     | Battery records can be viewed; relevant battery information is displayed; supported battery management operations are available.                     | Completed |
| PB11 | As an administrator, I want to manage customers so that I can review customer information.                    | Medium   | Customer records can be viewed; relevant customer information is displayed; supported customer management operations are available.                  | Completed |
| PB12 | As an administrator, I want to manage rental bookings so that I can review and process customer requests.     | High     | Rental bookings can be viewed; booking statuses are displayed; supported booking management actions are available.                                   | Completed |
| PB13 | As an administrator, I want to view reports so that I can review information about platform activity.         | Medium   | The reporting interface is accessible; relevant available data is retrieved; information is presented in a readable format.                          | Completed |
| PB14 | As a customer, I want to recover my forgotten password so that I can regain access to my account.             | Medium   | A password recovery option is available; the recovery request is processed by the configured workflow; appropriate feedback is displayed.            | Completed |

## 4. Prioritisation

The backlog prioritises features that support the main customer journey, including registration, login, battery browsing, and rental bookings. These features are important because they allow customers to access the platform and request a rental.

Administrative features support the management of batteries, customers, and bookings. Profile management, notifications, reporting, and password recovery support the broader user experience.

## 5. Definition of Done

A product backlog item should be considered complete when:

* The required functionality has been implemented.
* The feature has been tested against its requirements.
* Relevant validation and error handling have been considered.
* The feature works with the appropriate frontend and backend components, where applicable.
* Any identified defects affecting the requirement have been addressed.
* Available evidence, such as screenshots, tests, or GitHub commits, supports the completion claim.

## 6. Relationship to the Sprint Backlog

The product backlog identifies the features required for PowerShare. The sprint backlog breaks selected work into smaller tasks for development and tracking. This relationship helps the team move from identifying user needs to implementing individual features.

## 7. Conclusion

The product backlog provides a structured overview of PowerShare's intended functionality. It helps organise requirements, identify priorities, and connect development activities to customer and administrator needs.

**Portfolio note:** The backlog items and acceptance criteria above provide a structured representation of the PowerShare project. The completion statuses should be checked against the working application and supporting evidence before final submission. A simulated payment workflow should not be described as a live payment integration.

