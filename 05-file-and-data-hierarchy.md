# 05 — File and Data Hierarchy

## What is a File?

A **file** is a collection of related data stored together under a specific name.

### Example

```text
students.txt
```

A file such as `students.txt` can store:

- Student names
- Roll numbers
- Courses

In the DBMS context, files can be used to store related data such as:

- Student details
- Marks
- Fees
- Attendance

## Hierarchy of Data in a File

The hierarchy of data shows how small units of data are organized to form larger units.

```text
Bit → Byte / Character → Field → Record → File → Database
```

### 1. Bit

The **smallest unit of data**.

Example:

```text
0 or 1
```

### 2. Byte / Character

A group of bits representing a character.

Example:

```text
A
```

### 3. Field

One meaningful piece of data.

Example:

```text
Datta
```

### 4. Record

A collection of related fields.

Example:

```text
101, Datta, BCA
```

### 5. File

A collection of related records.

Example:

```text
Student File
```

### 6. Database

A collection of related data/files organized for use.
