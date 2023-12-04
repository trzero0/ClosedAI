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

[![diagram]([![](https://mermaid.ink/img/pako:eNplUc1uwjAMfhUrJ5AQl2mX3hgIxmFSpe3Yi0lMG9bEneMKMcS7L10PBeFDFH9_ku2rsezIFCb46AJ2VQQQZp3N1i0ncqs9HL1GSglU0H77WEO6JKUASaW32gvN54ML4J2TZn5shhKKjmRpOYzYBhUPmGhSrH6zf2qHKnNKLZR-2hEvhU9kNU2qrXDUHP3oE0KrcKYDYNc9Ul_o23OeD9bpLuYtj5NTYFXuH-XdRRuOsMWkT9y6Qd11Ci_L12fjjrluCbZeaBrz_jULE0gCepc3fh2wymhDgSpT5G_r60YrU8VbFmKv_HmJ1hR5z7QwfedQaeOxFgymOGKbMkrOK8vHeMP_U97-AAZPiqg?type=png)](https://mermaid.live/edit#pako:eNplUc1uwjAMfhUrJ5AQl2mX3hgIxmFSpe3Yi0lMG9bEneMKMcS7L10PBeFDFH9_ku2rsezIFCb46AJ2VQQQZp3N1i0ncqs9HL1GSglU0H77WEO6JKUASaW32gvN54ML4J2TZn5shhKKjmRpOYzYBhUPmGhSrH6zf2qHKnNKLZR-2hEvhU9kNU2qrXDUHP3oE0KrcKYDYNc9Ul_o23OeD9bpLuYtj5NTYFXuH-XdRRuOsMWkT9y6Qd11Ci_L12fjjrluCbZeaBrz_jULE0gCepc3fh2wymhDgSpT5G_r60YrU8VbFmKv_HmJ1hR5z7QwfedQaeOxFgymOGKbMkrOK8vHeMP_U97-AAZPiqg))


### Database
#### Entity Relationship Diagram
[![diagram](https://mermaid.ink/img/pako:eNp1kc9qwzAMxl_F6Ny-gM_rdhoMxtglYNRYaUwTK8gOW0nz7lPSGtaw3Wx9P336N0HNnsACyVPAk2BfRWM-Eom5Xvd7nswLRa8_a1pMi_YsQSOpDYOZeSVW2prmJpR8d_gmqUOiYnTHjtRxPCWXeSE_Wc48ZvfWYdyAtRBm8u54-QVumIGkYen_ox7ctUPuOv5aO9w2VxLVEiU7bv6CHsfSUTBpZY6wg56kx-B1kdOSWUFuqacKrD49yrmCKs7K4Zj5_RJrsFlG2sE4eB3yvvoSJB8yy-vtMOt9CnhYFbANdonmH3u5m64?type=png)](https://mermaid.live/edit#pako:eNp1kc9qwzAMxl_F6Ny-gM_rdhoMxtglYNRYaUwTK8gOW0nz7lPSGtaw3Wx9P336N0HNnsACyVPAk2BfRWM-Eom5Xvd7nswLRa8_a1pMi_YsQSOpDYOZeSVW2prmJpR8d_gmqUOiYnTHjtRxPCWXeSE_Wc48ZvfWYdyAtRBm8u54-QVumIGkYen_ox7ctUPuOv5aO9w2VxLVEiU7bv6CHsfSUTBpZY6wg56kx-B1kdOSWUFuqacKrD49yrmCKs7K4Zj5_RJrsFlG2sE4eB3yvvoSJB8yy-vtMOt9CnhYFbANdonmH3u5m64)

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
