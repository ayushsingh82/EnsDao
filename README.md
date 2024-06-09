# EnsDAO URI Creation and Publication Guide

This guide provides a comprehensive step-by-step process for creating and publishing a DAO URI using the DAO Metadata Standard (EIP-4824). The DAO URI centralizes essential metadata about your DAO, making it easily accessible and transparent.

## Overview

**EIP-4824** introduces the `daoURI`, a unified URI that consolidates a DAO's metadata, including governance, proposals, members, activities, and more. This standard provides a comprehensive overview of the DAO's operations, which are often spread across multiple platforms.

## Prerequisites

Before you begin, ensure you have:
- Access to the Ethereum Mainnet.
- An Ethereum Name Service (ENS) domain.
- Relevant URIs for your DAO's members, activity log, proposals, issuers, and contracts registry (if applicable).

## Steps to Create and Publish DAO URI

### 1. Network

Ensure you are connected to the **Mainnet**.

### 2. DAO Metadata

Fill in the following details to create your DAO URI:

- **Name**: Enter the name of your DAO.
- **Description**: Provide a brief description of your DAO.
- **Framework**: Specify the framework of your DAO (e.g., Custom).

### 3. Metadata URIs

Provide the URIs for the following components of your DAO:

- **Members URI**: Enter the URI that lists your DAO members.
- **Activity Log URI**: Enter the URI that logs your DAO's activities.
- **Proposals URI**: Enter the URI that lists your DAO's proposals.
- **Issuers URI**: Enter the URI for issuers within your DAO.
- **Contract Registry URI (optional)**: Enter the URI to your DAO's contracts registry, if available.
- **Manager Address (optional)**: Enter the Ethereum address of your DAO manager, if applicable.
- **Governance Document (optional)**: Enter the URI to your DAO's governance document (preferably in Markdown format).

### 4. Agree and Publish

Agree to create the `daoURI` text record in your ENS domain. This step links the metadata to your DAO's ENS domain.


