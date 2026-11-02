# GoIT React Homework #1

This project is the first homework assignment within the GoIT React Developer program. It focuses on foundational React concepts including component-based architecture, props passing, conditional styling, list rendering, CSS modules, and external JSON data management using Vite.

## 🚀 Live Demo
- [View Live Application on Vercel](https://goit-react-hw-01-lovat-ten.vercel.app/)

## 🛠️ Components Included
1. **Profile (`<Profile>`):** Displays user social media profile details (avatar, name, tag, location) and follower statistics (followers, views, likes) utilizing data imported from `userData.json`.
2. **Friend List (`<FriendList>` & `<FriendListItem>`):** Renders a dynamic list of friends with their avatars, names, and online/offline status indicators (`isOnlie` conditional styling) using data from `friends.json`.
3. **Transaction History (`<TransactionHistory>`):** Displays a structured financial ledger table outlining transaction types, amounts, and currencies using data imported from `transactions.json`.

## 📂 Project Structure
- `src/components/Profile/` — Profile component & CSS module (`Profile.jsx`, `Profile.module.css`)
- `src/components/FriendList/` — FriendList & FriendListItem components & CSS modules
- `src/components/TransactionHistory/` — TransactionHistory component & CSS module
- `src/` — JSON data files (`userData.json`, `friends.json`, `transactions.json`) and root `App.jsx`

## 🛠️ Technologies & Tools Used
- **React (v18+):** Functional components and props.
- **Bundler:** Vite.
- **Styling:** CSS Modules for scoped component styling.
- **Data Management:** JSON files for clean separation of concerns.
- **Version Control & Deployment:** Git, GitHub, and Vercel.