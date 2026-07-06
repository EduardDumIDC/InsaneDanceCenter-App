# Database Schema

# Insane Dance Center App

Version: 0.1

---

## studios

- id
- name
- logo
- phone
- email
- address
- created_at

---

## users

- id
- studio_id
- first_name
- last_name
- email
- phone
- role
- status
- created_at

Roles:
- administrator
- antrenor
- asistent

---

## groups

- id
- studio_id
- name
- color
- active
- created_at

---

## students

- id
- studio_id
- group_id
- first_name
- last_name
- birth_date
- mother_name
- mother_phone
- father_name
- father_phone
- emergency_contact
- emergency_phone
- medical_notes
- status
- created_at

Status:
- activ
- proba
- pauza
- inactiv

---

## rooms

- id
- studio_id
- name

Default:
- Sala 1
- Sala 2

---

## activities

- id
- studio_id
- group_id
- room_id
- trainer_id
- assistant_id
- activity_type
- date
- start_time
- end_time
- notes
- created_at

---

## attendance

- id
- activity_id
- student_id
- status
- created_at

Status:
- prezent
- absent
- necompletat

---

## competitions

- id
- studio_id
- name
- location
- organizer
- date
- notes
- created_at

---

## competition_results

- id
- competition_id
- student_id
- category
- result_type_id
- created_at

---

## result_types

- id
- studio_id
- name
- sort_order
- active

Examples:
- Locul I
- Locul II
- Locul III
- Top 8
- Killer of the Class
- Best Dancer

---

## todos

- id
- studio_id
- title
- description
- assigned_to
- deadline
- status
- completed_at
- created_at

Status:
- de_facut
- in_lucru
- finalizat
- intarziat

---

## announcements

- id
- studio_id
- title
- message
- target_type
- target_id
- created_by
- created_at

Target type:
- general
- grupa
- persoana

---

## seasons

- id
- studio_id
- name
- active
- created_at

Example:
- 2026-2027

---

## student_history

- id
- student_id
- date
- type
- description
- created_by
- created_at
