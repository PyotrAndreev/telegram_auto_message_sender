# Telegram Auto Message Sender
a Python-based application that allows Telegram users to establish automated reminders and messaging tasks. It supports two modes of interaction: users can send automated messages at regular intervals from their own Telegram account to others, or direct messages to themselves using a bot powered.

## Table of Contents
- [Goal](#Goal)
- [Features](#Features)
- [Technical Framework](#Technical-Framework)
- [Project Plan](#Project-Plan)
- [Future Plans](#Future-Plans)
- [Developers](#Developers)

## Goal: 
To enable Telegram users to set up automated reminders and messages, either through their own account or via a bot, with customizable repetition intervals and recipient lists.

## Features:
- **Message Repetition**: Users can set intervals for message repetition.
- **Reminder Management**: Track and manage current reminders, with options to activate or deactivate them.
- **Reminder Scheduling**: Default start is the creation moment; reminders run indefinitely unless a specific end time is set.
- **Recipient Customization**: If linked with Pyrogram, users can add specific Telegram accounts as recipients for each reminder.
- **Two Interaction Modes**:
  - Via Pyrogram for sending messages from user accounts.
  - Via Aiogram or aiogram_dialog for reminders through a bot.

## Technical Framework:
- Python-based, utilizing Pyrogram and Aiogram/aiogram_dialog.
- Structured in blocks for computation, Telegram service connection, and database management.

## Project Plan:
Phase 1: Initial Setup and Framework (Duration: 2 weeks)
- Task 1: Set up the project repository on GitHub.
- Task 2: Establish the basic Python environment and dependencies (Pyrogram, Aiogram).
- Task 3: Design the database schema for storing user data and reminders.

Phase 2: Core Functionality Development (Duration: 4 weeks)
- Task 4: Develop the computation block for managing reminders and recipients.
- Task 5: Implement connection with Telegram via Aiogram/aiogram_dialog.
- Task 6: Create functionality for users to link their Telegram accounts using Pyrogram.
- Task 7: Develop the reminder repetition and scheduling features.

Phase 3: Testing and Refinement (Duration: 3 weeks)
- Task 8: Conduct thorough testing of all functionalities.
- Task 9: Refine the user interface and experience.
- Task 10: Ensure robust error handling and security measures.

Phase 4: Documentation and Release (Duration: 1 week)
- Task 11: Prepare comprehensive documentation and usage instructions.
- Task 12: Release the first version of the Telegram Reminder Bot.
- Task 13: Gather initial user feedback for future improvements.

## Future Plans:
- Integration with additional messaging platforms.
- Advanced message customization (attachments, rich text).
- User analytics for tracking message effectiveness.
- Enhanced security features, like two-factor authentication.

## Developers:
Lead Developer: [PyotrAndreev]
Python Developer: [kiyomiqqq]
