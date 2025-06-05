# INSTAGRAM-CLONE
# 📸 Instagram Clone - MySQL Relational Database Design

This project is a mini-clone of Instagram's backend using MySQL. It demonstrates a simplified version of how social media applications can model users, photos, likes, comments, followers, and tags.

## 🗂️ Database Schema

The database `instagram_clone_db` includes the following tables:

- **users**: Stores user information
- **photos**: Holds uploaded image data
- **comments**: Manages photo comments
- **likes**: Tracks which users liked which photos
- **follows**: Tracks user follow relationships
- **tags**: List of tags available
- **photo_tags**: Mapping between photos and tags

### 🔗 Relationships
- One-to-many: Users → Photos, Users → Comments
- Many-to-many: Users ↔ Likes, Users ↔ Follows, Photos ↔ Tags

## 📦 Features Implemented

- Add users and simulate real-time signup timestamps
- Upload photos tied to specific users
- Enable comments and likes on photos
- Support for tagging photos
- Track who follows whom
- Query top tags, most liked photo, user activity stats, and more

## 📊 Sample Queries

- Average posts per user
- Users with no posts
- Most active day for new user signups
- Most liked photo
- Most used tags
- Users who liked all photos

## 💻 Technologies Used

- MySQL (relational database)
- SQL queries (DML & DDL)

## 🚀 How to Use

1. Run the SQL script in MySQL Workbench or any compatible client
2. Explore data with provided SELECT queries
3. Extend functionality by adding stored procedures or triggers

## 📈 Future Improvements

- Add stored procedures and triggers
- Integrate with a backend API
- Use views for analytics dashboards

 
