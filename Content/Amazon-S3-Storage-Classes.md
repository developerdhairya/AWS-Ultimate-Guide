# Amazon S3 Storage Classes

---

### Amazon S3 Standard

- Designed for frequently accessed data
- Stores data in a minimum of three Availability Zones thus provide high availability.
- Ideal for  static websites, content distribution, and data analytics
- Higher cost than other storage classes intended for infrequently accessed data and archival storage.

### Amazon S3 Standard-Infrequent Access (S3 Standard-IA)

- Similar to Amazon S3 Standard but has a lower storage price and higher retrieval price.
- Ideal for data infrequently accessed but requires high availability when needed.
- Stores data in a minimum of three Availability Zones thus provide same availability as S3 standard.

### Amazon S3 One Zone-Infrequent Access (S3 One Zone-IA)

- Similar to S3 Standard-IA nut stores data in a single Availability Zone
- Has a lower storage price than Amazon S3 Standard-IA.

### Amazon S3 Intelligent Tiering

- Amazon S3 monitors objects’ access patterns.
- Ideal for data with unknown or changing access patterns.
- If you haven’t accessed an object for 30 consecutive days, Amazon S3 automatically moves it to  Amazon S3 Standard-IA and moves back to Amazon S3 Standard when you access.

### Amazon S3 Glacier

- Ideal for keeping archived data.
- You can either simply move data to it or you can create vaults and populate them with archives.
- If you have compliance requirements for retaining data for certain period of time,you can use S3 Glacier vault lock policy and lock your vaults.
- You can specify controls like write once and read many(WORM) in a vault’s lock policy and lock the vault for future edits.
- Once locked the policy can’t be changed.
- We have 3 types of AWS S3 Glacier:
  - Amazon S3 Glacier Instant Retrieval.(Same availability as S3 standard)
  - Amazon S3 Glacier Flexible Retrieval.(few minutes to few hours)
  - Amazon S3 Glacier Deep Archive(within 12 hours)

### Amazon S3 outpost

- On-premise deployment.
