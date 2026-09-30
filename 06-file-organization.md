# 06 — File Organization

## What is File Organization?

**File organization is the method of arranging and storing records in a file for efficient access and management.**

In simple words, it tells us **how records are arranged inside a file** so that we can access and manage them efficiently.

## Main Types

1. Sequential File Organization
2. Indexed File Organization
3. Direct / Random File Organization

---

## 1. Sequential File Organization

In **sequential file organization**, records are stored one after another, usually in a particular order.

### Example

| Roll No. | Name |
|---:|---|
| 101 | Datta |
| 102 | Rahul |
| 103 | Amit |
| 104 | Aditya |

The records are stored one after another.

### Easy Example

It is like reading a book **page by page**. You normally go through the pages in sequence.

---

## 2. Indexed File Organization

An **index** is used to quickly find where a record is stored.

### Think About a Textbook

Instead of checking every page for **"Normalization"**, you look at the index:

```text
Normalization → Page 45
Keys          → Page 30
SQL           → Page 60
```

Then you directly go to the required page.

> **Indexed file organization uses an index to locate records quickly.**

---

## 3. Direct / Random File Organization

In **direct/random file organization**, the system can directly access a record using its location or key.

### Example

```text
Roll No. 105 → Directly find record 105
```

Instead of checking records one by one, the system can directly access the required record.

---

# File Attributes

**File attributes are the properties or information that describe a file.**

| Attribute | Meaning | Example |
|---|---|---|
| Name | Name of the file | DBMS.pdf |
| Type / Format | Type or format of file | PDF |
| Location | Where the file is stored | Documents/ |
| Size | Storage occupied | 5 MB |
| Protection | Who can access/modify | Read / Write |
| Time & Date | Creation, modification, or access time | 1 Oct 2026 |

---

# Basic File Operations

| Operation | Meaning |
|---|---|
| Create | Creates a new file |
| Open | Opens a file for use |
| Close | Closes the file after use |
| Read | Gets data from a file |
| Write | Stores data in a file |
| Search | Finds specific data in a file |
| Insert | Adds new data to a file |
| Update | Changes existing data in a file |

---

# Objectives of File Organization

The main objectives are:

1. Faster selection and retrieval of records
2. Easy and fast insert, delete, and update operations
3. Prevents duplicate records
4. Efficient storage of records with minimum storage cost

---

## Quick Memory

```text
File Organization
├── Sequential
├── Indexed
└── Direct / Random
```
