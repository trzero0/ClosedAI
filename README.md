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

[![diagram](https://mermaid.ink/img/pako:eNpVkcFqwzAMhl9F-NRC2QPk1q10K2yQ0Wsuqq2m3mIrkxRGKH33OQssqw7G_v9Plvl9dZ4DucqlmEPCvskAwmyr1VPHSmF7gHO0TKpggv4z5hZ0VKMEajJ4G4TW66kL4IXVij8fphLKgeTBc5q1HRqeUGkhnpnbjqDMGgIc318XZ6q6XNgK6Vc367XwB3nThdoLZytT7vuE0Bt80wmw7xfrsby_sLCtD_d8P9qFM-xR7c_7v7qNSyQJYyhBXSetcXahRI2ryraL7cUa1-RbAXEwPo7Zu6rEQxs39AGNdhFbweSqM3ZaVArRWN7m6H9_4PYDCUB4yQ?type=png)](https://mermaid.live/edit#pako:eNpVkcFqwzAMhl9F-NRC2QPk1q10K2yQ0Wsuqq2m3mIrkxRGKH33OQssqw7G_v9Plvl9dZ4DucqlmEPCvskAwmyr1VPHSmF7gHO0TKpggv4z5hZ0VKMEajJ4G4TW66kL4IXVij8fphLKgeTBc5q1HRqeUGkhnpnbjqDMGgIc318XZ6q6XNgK6Vc367XwB3nThdoLZytT7vuE0Bt80wmw7xfrsby_sLCtD_d8P9qFM-xR7c_7v7qNSyQJYyhBXSetcXahRI2ryraL7cUa1-RbAXEwPo7Zu6rEQxs39AGNdhFbweSqM3ZaVArRWN7m6H9_4PYDCUB4yQ](https://www.mermaidchart.com/app/projects/187c5144-11fe-4486-af55-dafae3f9de8a/diagrams/a2621537-cbc5-47e1-b6a0-b1ca4b878380/version/v0.1/edit))

### Database

#### Entity Relationship Diagram

[![diagram]([https://mermaid.ink/img/pako:eNp1kc9qwzAMxl_F6Ny-gM_rdhoMxtglYNRYaUwTK8gOW0nz7lPSGtaw3Wx9P336N0HNnsACyVPAk2BfRWM-Eom5Xvd7nswLRa8_a1pMi_YsQSOpDYOZeSVW2prmJpR8d_gmqUOiYnTHjtRxPCWXeSE_Wc48ZvfWYdyAtRBm8u54-QVumIGkYen_ox7ctUPuOv5aO9w2VxLVEiU7bv6CHsfSUTBpZY6wg56kx-B1kdOSWUFuqacKrD49yrmCKs7K4Zj5_RJrsFlG2sE4eB3yvvoSJB8yy-vtMOt9CnhYFbANdonmH3u5m64?type=png)](https://mermaid.live/edit#pako:eNp1kc9qwzAMxl_F6Ny-gM_rdhoMxtglYNRYaUwTK8gOW0nz7lPSGtaw3Wx9P336N0HNnsACyVPAk2BfRWM-Eom5Xvd7nswLRa8_a1pMi_YsQSOpDYOZeSVW2prmJpR8d_gmqUOiYnTHjtRxPCWXeSE_Wc48ZvfWYdyAtRBm8u54-QVumIGkYen_ox7ctUPuOv5aO9w2VxLVEiU7bv6CHsfSUTBpZY6wg56kx-B1kdOSWUFuqacKrD49yrmCKs7K4Zj5_RJrsFlG2sE4eB3yvvoSJB8yy-vtMOt9CnhYFbANdonmH3u5m64](https://www.mermaidchart.com/raw/a2621537-cbc5-47e1-b6a0-b1ca4b878380?theme=light&version=v0.1&format=svg))

#### Relational Schema

![schema](https://showme.redstarplugin.com/d/d:TLh8GPIp)


## Code

### Database table creation sql

```sql
-- User Table
CREATE TABLE user
(
  user_id INT NOT NULL,
  name VARCHAR(50) NOT NULL,
  email VARCHAR(255) NOT NULL,
  password_hash VARCHAR(500) NOT NULL,
  auth_token VARCHAR(500) NOT NULL,
  height FLOAT NOT NULL,
  weight FLOAT NOT NULL,
  gender_id INT NOT NULL,
  friend_code VARCHAR(50) UNIQUE NOT NULL,
  PRIMARY KEY (user_id),
  UNIQUE (email),
  FOREIGN KEY (gender_id) REFERENCES gender(gender_id)
);

-- Gender Table
CREATE TABLE gender
(
  gender_id INT NOT NULL,
  name VARCHAR(50) NOT NULL,
  PRIMARY KEY (gender_id)
);

-- Friendship Table
CREATE TABLE friendship
(
  user1_id INT NOT NULL,
  user2_id INT NOT NULL,
  status ENUM('PENDING', 'ACCEPTED') NOT NULL,
  PRIMARY KEY (user1_id, user2_id),
  FOREIGN KEY (user1_id) REFERENCES user(user_id),
  FOREIGN KEY (user2_id) REFERENCES user(user_id)
);

-- User Exercise Table
CREATE TABLE user_exercise
(
  user_exercise_id INT NOT NULL,
  name VARCHAR(50) NOT NULL,
  description VARCHAR(500),
  video_url VARCHAR(500),
  user_id INT NOT NULL,
  PRIMARY KEY (user_exercise_id),
  FOREIGN KEY (user_id) REFERENCES user(user_id)
);

-- Workout Plan Table
CREATE TABLE workout_plan
(
  plan_id INT NOT NULL,
  name VARCHAR(500) NOT NULL,
  is_private INT NOT NULL,
  user_id INT NOT NULL,
  PRIMARY KEY (plan_id),
  FOREIGN KEY (user_id) REFERENCES user(user_id)
);

-- Workout Table
CREATE TABLE workout
(
  workout_id INT NOT NULL,
  name VARCHAR(50) NOT NULL,
  date DATE NOT NULL,
  user_id INT NOT NULL,
  plan_id INT,
  PRIMARY KEY (workout_id),
  FOREIGN KEY (user_id) REFERENCES user(user_id),
  FOREIGN KEY (plan_id) REFERENCES workout_plan(plan_id)
);

-- Exercise Table
CREATE TABLE exercise
(
  exercise_id INT NOT NULL,
  user_exercise_id INT,
  set INT NOT NULL,
  repetition INT NOT NULL,
  rating FLOAT NOT NULL,
  duration INT NOT NULL,
  workout_id INT NOT NULL,
  PRIMARY KEY (exercise_id),
  FOREIGN KEY (workout_id) REFERENCES workout(workout_id),
  FOREIGN KEY (user_exercise_id) REFERENCES user_exercise(user_exercise_id)
);
```
