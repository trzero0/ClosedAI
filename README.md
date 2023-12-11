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

[![diagram](https://mermaid.ink/img/pako:eNplUc1uwjAMfhUrJ5AQl2mX3hgIxmFSpe3Yi0lMG9bEneMKMcS7L10PBeFDFH9_ku2rsezIFCb46AJ2VQQQZp3N1i0ncqs9HL1GSglU0H77WEO6JKUASaW32gvN54ML4J2TZn5shhKKjmRpOYzYBhUPmGhSrH6zf2qHKnNKLZR-2hEvhU9kNU2qrXDUHP3oE0KrcKYDYNc9Ul_o23OeD9bpLuYtj5NTYFXuH-XdRRuOsMWkT9y6Qd11Ci_L12fjjrluCbZeaBrz_jULE0gCepc3fh2wymhDgSpT5G_r60YrU8VbFmKv_HmJ1hR5z7QwfedQaeOxFgymOGKbMkrOK8vHeMP_U97-AAZPiqg?type=png)](https://mermaid.live/edit#pako:eNplUc1uwjAMfhUrJ5AQl2mX3hgIxmFSpe3Yi0lMG9bEneMKMcS7L10PBeFDFH9_ku2rsezIFCb46AJ2VQQQZp3N1i0ncqs9HL1GSglU0H77WEO6JKUASaW32gvN54ML4J2TZn5shhKKjmRpOYzYBhUPmGhSrH6zf2qHKnNKLZR-2hEvhU9kNU2qrXDUHP3oE0KrcKYDYNc9Ul_o23OeD9bpLuYtj5NTYFXuH-XdRRuOsMWkT9y6Qd11Ci_L12fjjrluCbZeaBrz_jULE0gCepc3fh2wymhDgSpT5G_r60YrU8VbFmKv_HmJ1hR5z7QwfedQaeOxFgymOGKbMkrOK8vHeMP_U97-AAZPiqg)


### Database

#### Entity Relationship Diagram

[![diagram](https://mermaid.ink/img/pako:eNrVVL1u2zAQfhWCk4smL6ChQNp6KNAGRoskQ9SBIc_0wRQpkCc7RuB3L6lQssJI7dxF4n387v-OL1w6Bbzi0ogQvqLQXjS1ZayX2V0Az16SzNjHLgpWNFCxQB6tzjA0Ak2BzdDaaO_ovCpgoSMRLWXxCKh3VLGtcWLAdjOYBqvAF7Y8aAwEfvWhYgeHKsPGabRT7FzbS4o3bWtQCkJnx0wDCU-LGg_O711HP0G6polxvNVtvUs1vJ0p1DN4iQHCgD_-HvyJA2xe9f7ldfQzWLtHBW7B07v6tGFa7AD0RiZsUk0vgFDqFo7Z82JkMfItGvh_5qR9DXiDkjoPX3bCaihmJnXkobd3Z5FWXfwMRgoi0MbjQcjTCkN_ohjok3MGhF2q2Dr3ZyzZTB3K5pTNO8WWdE_wHe2-0CShy8a376zH_GYa2u_79fWn6VZUCQ3pdroqiZTYy7eza3Khj67y-PzFxEVpWIKJXsU-g3FWB0aupKzHPfhmpelUMlJbfsXjnMdpVPHd6ztQc9pBAzWv4lEJv695bc-RJzpyv05W8morTIAr3rUxD8jv5IiCQnL-R35J029grvubTDz_Af2hzqY?type=png)](https://mermaid.live/edit#pako:eNrVVL1u2zAQfhWCk4smL6ChQNp6KNAGRoskQ9SBIc_0wRQpkCc7RuB3L6lQssJI7dxF4n387v-OL1w6Bbzi0ogQvqLQXjS1ZayX2V0Az16SzNjHLgpWNFCxQB6tzjA0Ak2BzdDaaO_ovCpgoSMRLWXxCKh3VLGtcWLAdjOYBqvAF7Y8aAwEfvWhYgeHKsPGabRT7FzbS4o3bWtQCkJnx0wDCU-LGg_O711HP0G6polxvNVtvUs1vJ0p1DN4iQHCgD_-HvyJA2xe9f7ldfQzWLtHBW7B07v6tGFa7AD0RiZsUk0vgFDqFo7Z82JkMfItGvh_5qR9DXiDkjoPX3bCaihmJnXkobd3Z5FWXfwMRgoi0MbjQcjTCkN_ohjok3MGhF2q2Dr3ZyzZTB3K5pTNO8WWdE_wHe2-0CShy8a376zH_GYa2u_79fWn6VZUCQ3pdroqiZTYy7eza3Khj67y-PzFxEVpWIKJXsU-g3FWB0aupKzHPfhmpelUMlJbfsXjnMdpVPHd6ztQc9pBAzWv4lEJv695bc-RJzpyv05W8morTIAr3rUxD8jv5IiCQnL-R35J029grvubTDz_Af2hzqY)

#### Relational Schema

[![schema](https://mermaid.ink/img/pako:eNqNVctuozAU_RWLdfsD2UUN7WQ6aisgmllEslx8A1clNuNHH9Pk38dAKNiQtqzQPYdz7svmPcolh2gRgVohKxTbbwVxzyaNE3I4XF7Kd_L7Prm932RkQUqmp_B1so7vVumP9YNjoECDzMBXPAU54PMcLVlm67sbRynm8fhPnFyt09gxcgWD1SBP02yZbdJZXw47FP0nfWF-nXS1zOK2lLyy_Ax3nIUUhqE48bLlTcihTczxXK6FVPivl_zQCCv3m-PRDodQtkLxBJyaUklblKN-vXfvzYPCEKtBUeTk4XaIa6NQFKRWcocV0BpzalU1wQXbwyQIe4YjKnfVkUdUpqTN6wDsKskMKQGL0oTRlyBagOAuSxB2f3qf2O4UOoA2Wzutg2n9IhWnbk_LAWV5Lq0w1LzV0GmPIwPvUcoKmCAcNXusgA_Iz_T-jsCrUawpjnXA8dzeBY3Xhhmrp61vo206Q38nmqFYV74usQ4FxzO-vp37ag4Zkhsj9i8djMjmykuuPwlBZq7xT9KaMyvmr9C5XPsJoKa1wuePPfKduwMa2M90Y5TR2KTdVH9He99c7usKTD_643CkAzfDii8LPfrHl87IwCuoHDV0WheT6XzYDFCg-rni906yu-NyhbVBKSbYM3KQ_qXw2aJpMH5AQQ0Gfekmzq1ifnT-Rmg1avhysKe2nK7QoCmNlZgMrDPssO9VN25uYPxrObWt2NS0vUmUpckmiBlFs-QkGV1Ee1DufuXux9yKbiNTghtdtHCvnKmnbbQVDY9ZI9M3kUcLoyxcRLZuNvv0K_eDMUcjVbTYsUrD8T9LE2Fk?type=png)](https://mermaid.live/edit#pako:eNqNVctuozAU_RWLdfsD2UUN7WQ6aisgmllEslx8A1clNuNHH9Pk38dAKNiQtqzQPYdz7svmPcolh2gRgVohKxTbbwVxzyaNE3I4XF7Kd_L7Prm932RkQUqmp_B1so7vVumP9YNjoECDzMBXPAU54PMcLVlm67sbRynm8fhPnFyt09gxcgWD1SBP02yZbdJZXw47FP0nfWF-nXS1zOK2lLyy_Ax3nIUUhqE48bLlTcihTczxXK6FVPivl_zQCCv3m-PRDodQtkLxBJyaUklblKN-vXfvzYPCEKtBUeTk4XaIa6NQFKRWcocV0BpzalU1wQXbwyQIe4YjKnfVkUdUpqTN6wDsKskMKQGL0oTRlyBagOAuSxB2f3qf2O4UOoA2Wzutg2n9IhWnbk_LAWV5Lq0w1LzV0GmPIwPvUcoKmCAcNXusgA_Iz_T-jsCrUawpjnXA8dzeBY3Xhhmrp61vo206Q38nmqFYV74usQ4FxzO-vp37ag4Zkhsj9i8djMjmykuuPwlBZq7xT9KaMyvmr9C5XPsJoKa1wuePPfKduwMa2M90Y5TR2KTdVH9He99c7usKTD_643CkAzfDii8LPfrHl87IwCuoHDV0WheT6XzYDFCg-rni906yu-NyhbVBKSbYM3KQ_qXw2aJpMH5AQQ0Gfekmzq1ifnT-Rmg1avhysKe2nK7QoCmNlZgMrDPssO9VN25uYPxrObWt2NS0vUmUpckmiBlFs-QkGV1Ee1DufuXux9yKbiNTghtdtHCvnKmnbbQVDY9ZI9M3kUcLoyxcRLZuNvv0K_eDMUcjVbTYsUrD8T9LE2Fk)
