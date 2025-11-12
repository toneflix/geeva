# Geeva Frontend

This repository contains the frontend for **Geeva**, a social giveaway platform where users can create, fund, and participate in giveaways. Built with **Next.js**, **TailwindCSS**, and **shadcn/ui**, the app is designed to be modular, scalable, and easy to contribute to.

## About

Geeva allows users to:

- Create prefunded giveaways with clear rules and rewards.
- Participate in giveaways by submitting entries or completing tasks.
- Follow other users to see their personalized timeline of posts.
- View real-time stats on posts, including remaining balance, number of entries, and winners.

The frontend connects to a backend API (NestJS recommended) and is designed for seamless integration with the Stellar blockchain for escrow and payout automation.

## Features

- Timeline feed of active and past giveaways
- Post creation modal with optional task/proof requirements
- Entry form with optional file upload for proof
- User profile pages showing personal posts and entries
- Follow/unfollow functionality
- Wallet overview and transaction history
- Modular, reusable React components

## Tech Stack

- **Framework**: Next.js
- **Styling**: TailwindCSS
- **UI Components**: shadcn/ui
- **State Management**: Zustand or React Context
- **API Requests**: Axios
- **Blockchain Integration**: Stellar SDK (for wallets, escrow, and payouts)

## Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/your-feature`
3. Commit your changes: `git commit -m "Add some feature"`
4. Push to the branch: `git push origin feature/your-feature`
5. Open a pull request

Ensure your code follows existing conventions, and include tests where applicable.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
