# Harmony OS

# INSTALLATION

This document provides a detailed guide for installing HarmonyOS on supported Huawei devices and development environments. It begins with checking device compatibility using the “My Huawei” app or the official Huawei website, followed by downloading the necessary tools such as the HarmonyOS update package or the DevEco Studio IDE for emulation. The guide then walks through steps to create a Huawei ID, back up important data, and initiate the installation process via the system settings or development platform.

Next, the document outlines the step-by-step installation procedure, including downloading HarmonyOS, verifying the update, and initiating the system reboot for installation. After installation is complete, the guide explains how to verify the HarmonyOS version, restore backed-up data, and explore new features such as the Super Device interface and distributed task management.
# System Call
The document provides an overview of system call implementation in HarmonyOS, with a specific focus on creating a custom kill() system call. This function allows one process to send signals—such as termination requests—to another, enhancing process control within the operating system. It is particularly relevant in system-level programming where secure, low-level communication between processes is required. A detailed step-by-step explanation illustrates how to define, implement, register, and test the kill() system call in the HarmonyOS microkernel, highlighting both kernel-side integration and user-space access. Since HarmonyOS employs a microkernel architecture and developer tools like DevEco Studio, the implementation approach is distinct but conceptually aligned with standard POSIX-compliant systems.
