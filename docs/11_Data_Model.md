# 11 - Data Model

---

# Purpose

This document defines how portfolio data is stored.

The application should separate content from presentation.

Portfolio information should never be hardcoded inside React components.

Instead, all content should be loaded from structured JSON files.

Updating the portfolio should only require editing JSON files.

---

# Design Principles

The data model should be:

- Human readable
- Easy to edit
- Scalable
- Consistent
- Independent from UI

Every portfolio category has its own JSON file.

---

# Data Directory

src/data/

personal.json

education.json

projects.json

internships.json

certifications.json

skills.json

languages.json

hobbies.json

socials.json

settings.json

---

# Personal Information

Fields

id

photo

name

birthDate

address

email

phone

about

---

# Education

Each education entry contains

id

type

institution

board

course

degree

minorDegree

stream

startYear

endYear

grade

location

image

description

---

# Projects

Each project contains

id

title

description

longDescription

technologies

features

date

status

github

demo

platform

images

video

---

# Internships

Each internship contains

id

organization

role

timeline

location

description

skillsUsed

certificate

website

---

# Certifications

Each certification contains

id

title

issuer

issueDate

expiryDate

credentialId

credentialUrl

certificateImage

description

---

# Skills

Each skill contains

id

name

category

experience

proficiency

icon

description

relatedProjects

---

# Languages

Each language contains

id

language

speaking

reading

writing

overall

countryPins

---

# Hobbies

Each hobby contains

id

name

description

icon

relatedObject

---

# Socials

Each social contains

id

platform

username

url

icon

displayOrder

---

# Settings

Contains configurable values.

Examples

Theme

Camera Speed

Mouse Sensitivity

Audio Volume

Language

Accessibility Options

Future settings should also be added here.

---

# Images

Images should not be embedded.

Only store file paths.

Example

/images/profile.png

/images/projects/project1.png

---

# Links

Store complete URLs.

Do not generate URLs inside components.

---

# IDs

Every record requires a unique ID.

IDs should remain stable.

Never use array indexes as identifiers.

---

# Ordering

Display order should be determined by the data.

The UI should not hardcode ordering.

---

# Optional Fields

Not every field is required.

Missing values should display placeholders.

The application should never crash due to missing data.

---

# Validation

Every JSON file should be validated during development.

Missing required fields should generate warnings.

---

# Future Expansion

Future portfolio sections should follow the same structure.

Every new category should receive its own JSON file.

Avoid mixing unrelated data into existing files.

---

# Success Criteria

The complete portfolio should be editable by modifying JSON files only.

No source code changes should be required to update portfolio content.
