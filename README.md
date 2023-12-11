# ClosedAI

## Fitness Tracker Documentation 🏃💨

[TOC]

## Introduction

The fitness tracker consist of 3 repositories

- [Documentation (this)](https://github.com/trzero0/ClosedAI)
- [Frontend](https://github.com/MughalAman/ClosedAI-Fitness-Tracker)
- [Backend](https://github.com/MughalAman/ClosedAI-Fitness-Tracker-API)

### Project Plan for Gym Training Web Application

#### **I. Goal Definition**
- Increase customer engagement and retention
- Grow revenue through potential subscription models or premium features
- Support data-driven decision-making in marketing and content production


#### **II. Scope Definition**
- **Included**: Customized workout programs, progress tracking, real-time feedback, interactive workout videos, progress analytics, virtual coaching, client management, and remote coaching for trainers and instructors.
- **Excluded**: E-commerce for gym equipment, diet planning and tracking, social media integration.


#### **III. Requirements Gathering**
- Conduct surveys, interviews, and focus group discussions with stakeholders, end-users, and other relevant parties.
- Document detailed requirements.


#### **IV. Functional Requirements**
- User authentication
- Customized workout program generation
- Progress tracking
- Real-time feedback
- Interactive workout videos
- Progress analytics
- Virtual coaching
- Client management for trainers and instructors


#### **V. Non-Functional Requirements**
- Performance: The application should be able to handle a large number of simultaneous users.
- Security: Ensure data protection and privacy.
- Scalability: Ability to grow and manage increased demand.

#### **VI. Resource Allocation**
- **Budget**: To be determined.
- **Personnel**: Frontend and backend developers, project manager.
- **Hardware/Software Tools**: VITE + React & Tailwind CSS for frontend, Python 3.11 FastAPI for backend, PostgreSQL for database.
- **Infrastructure**: Cloud hosting, CI/CD pipelines.

#### **VII. Risk Assessment**
- Identify potential risks such as project delays, budget overruns, technical issues, and develop mitigation strategies.

#### **VIII. Team Formation**
- Assign roles and responsibilities to team members.

#### **IX. Technology Stack Selections**
- **Frontend**: VITE + React & Tailwind CSS
- **Backend**: Python 3.11 FastAPI
- **Database**: PostgreSQL
- **Communication Platform**: Discord


#### **X. Communication Plan**
- Regular status updates and meetings on Discord.
- Use of project management tools for task tracking and collaboration.


#### **XI. Budgeting and Cost Estimation**
- Detailed budget breakdown including development, marketing, infrastructure costs, etc.


#### **XII. Client Involvement**
- Regular feedback sessions and updates.
- Ensure the product meets client expectations and needs.


#### **XIII. Legal and Compliance Considerations**
- Ensure the product complies with relevant laws and regulations regarding data protection and privacy.

## Diagrams & Schemas

### System structure

[![diagram](https://mermaid.ink/img/pako:eNpVkcFqwzAMhl9F-NRC2QPk1q10K2yQ0Wsuqq2m3mIrkxRGKH33OQssqw7G_v9Plvl9dZ4DucqlmEPCvskAwmyr1VPHSmF7gHO0TKpggv4z5hZ0VKMEajJ4G4TW66kL4IXVij8fphLKgeTBc5q1HRqeUGkhnpnbjqDMGgIc318XZ6q6XNgK6Vc367XwB3nThdoLZytT7vuE0Bt80wmw7xfrsby_sLCtD_d8P9qFM-xR7c_7v7qNSyQJYyhBXSetcXahRI2ryraL7cUa1-RbAXEwPo7Zu6rEQxs39AGNdhFbweSqM3ZaVArRWN7m6H9_4PYDCUB4yQ?type=png)](https://mermaid.live/edit#pako:eNpVkcFqwzAMhl9F-NRC2QPk1q10K2yQ0Wsuqq2m3mIrkxRGKH33OQssqw7G_v9Plvl9dZ4DucqlmEPCvskAwmyr1VPHSmF7gHO0TKpggv4z5hZ0VKMEajJ4G4TW66kL4IXVij8fphLKgeTBc5q1HRqeUGkhnpnbjqDMGgIc318XZ6q6XNgK6Vc367XwB3nThdoLZytT7vuE0Bt80wmw7xfrsby_sLCtD_d8P9qFM-xR7c_7v7qNSyQJYyhBXSetcXahRI2ryraL7cUa1-RbAXEwPo7Zu6rEQxs39AGNdhFbweSqM3ZaVArRWN7m6H9_4PYDCUB4yQ)

### Database

#### Entity Relationship Diagram

[![diagram](https://mermaid.ink/img/pako:eNqNVctuozAU_RWLdfsD2UUN7WQ6aisgmllEslx8A1clNuNHH9Pk38dAKNiQtqzQPYdz7svmPcolh2gRgVohKxTbbwVxzyaNE3I4XF7Kd_L7Prm932RkQUqmp_B1so7vVumP9YNjoECDzMBXPAU54PMcLVlm67sbRynm8fhPnFyt09gxcgWD1SBP02yZbdJZXw47FP0nfWF-nXS1zOK2lLyy_Ax3nIUUhqE48bLlTcihTczxXK6FVPivl_zQCCv3m-PRDodQtkLxBJyaUklblKN-vXfvzYPCEKtBUeTk4XaIa6NQFKRWcocV0BpzalU1wQXbwyQIe4YjKnfVkUdUpqTN6wDsKskMKQGL0oTRlyBagOAuSxB2f3qf2O4UOoA2Wzutg2n9IhWnbk_LAWV5Lq0w1LzV0GmPIwPvUcoKmCAcNXusgA_Iz_T-jsCrUawpjnXA8dzeBY3Xhhmrp61vo206Q38nmqFYV74usQ4FxzO-vp37ag4Zkhsj9i8djMjmykuuPwlBZq7xT9KaMyvmr9C5XPsJoKa1wuePPfKduwMa2M90Y5TR2KTdVH9He99c7usKTD_643CkAzfDii8LPfrHl87IwCuoHDV0WheT6XzYDFCg-rni906yu-NyhbVBKSbYM3KQ_qXw2aJpMH5AQQ0Gfekmzq1ifnT-Rmg1avhysKe2nK7QoCmNlZgMrDPssO9VN25uYPxrObWt2NS0vUmUpckmiBlFs-QkGV1Ee1DufuXux9yKbiNTghtdtHCvnKmnbbQVDY9ZI9M3kUcLoyxcRLZuNvv0K_eDMUcjVbTYsUrD8T9LE2Fk?type=png)](https://mermaid.live/edit#pako:eNqNVctuozAU_RWLdfsD2UUN7WQ6aisgmllEslx8A1clNuNHH9Pk38dAKNiQtqzQPYdz7svmPcolh2gRgVohKxTbbwVxzyaNE3I4XF7Kd_L7Prm932RkQUqmp_B1so7vVumP9YNjoECDzMBXPAU54PMcLVlm67sbRynm8fhPnFyt09gxcgWD1SBP02yZbdJZXw47FP0nfWF-nXS1zOK2lLyy_Ax3nIUUhqE48bLlTcihTczxXK6FVPivl_zQCCv3m-PRDodQtkLxBJyaUklblKN-vXfvzYPCEKtBUeTk4XaIa6NQFKRWcocV0BpzalU1wQXbwyQIe4YjKnfVkUdUpqTN6wDsKskMKQGL0oTRlyBagOAuSxB2f3qf2O4UOoA2Wzutg2n9IhWnbk_LAWV5Lq0w1LzV0GmPIwPvUcoKmCAcNXusgA_Iz_T-jsCrUawpjnXA8dzeBY3Xhhmrp61vo206Q38nmqFYV74usQ4FxzO-vp37ag4Zkhsj9i8djMjmykuuPwlBZq7xT9KaMyvmr9C5XPsJoKa1wuePPfKduwMa2M90Y5TR2KTdVH9He99c7usKTD_643CkAzfDii8LPfrHl87IwCuoHDV0WheT6XzYDFCg-rni906yu-NyhbVBKSbYM3KQ_qXw2aJpMH5AQQ0Gfekmzq1ifnT-Rmg1avhysKe2nK7QoCmNlZgMrDPssO9VN25uYPxrObWt2NS0vUmUpckmiBlFs-QkGV1Ee1DufuXux9yKbiNTghtdtHCvnKmnbbQVDY9ZI9M3kUcLoyxcRLZuNvv0K_eDMUcjVbTYsUrD8T9LE2Fk)

#### Relational Schema

![schema](https://showme.redstarplugin.com/d/d:TLh8GPIp)
