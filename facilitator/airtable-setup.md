---
layout: default
title: Airtable Setup & Reveal Guide
nav_order: 1
parent: Facilitator Portal
---

# Airtable Setup & Projector Reveal Guide

This guide outlines the steps for setting up the Airtable Base and preparing the live projector view for the 90-minute symposium workshop.

## Base & Table Configuration

1. Log in to Airtable and create a new base named **NASW 2026 Workshop**.
2. Rename the default table to **Submissions**.
3. Configure the table columns with these exact names and field types:
   * **Section** (Single Select):
     * `Breakout 1: Critical Pedagogy & Banking Models`
     * `Breakout 2: Systems Theory & Institutional Barriers`
     * `Breakout 3: Strengths-Based Mentorship Actions`
   * **Insight** (Long Text)
   * **Created Time** (Created Time - *Keep hidden on interface*)

## Personal Access Token (PAT) Setup

1. Go to [airtable.com/create/tokens](https://airtable.com/create/tokens).
2. Create a token with `data.records:write` scope and grant access to the **NASW 2026 Workshop** base.
3. Copy the token string and insert it into `AIRTABLE_PAT` in the Live Workshop Hub `_layouts/default.html` script.

## Live Projector Interface (Visual Reveal)

1. Click **Interfaces** in the top navigation bar of your Airtable base.
2. Select **Gallery / Card View** layout and connect it to the **Submissions** table.
3. Customize the display cards:
   * **Visible Fields**: Display **Insight** only.
   * **Hidden Fields**: Hide **Created Time** and **Record ID** to ensure full submission anonymity.
   * **Font Size**: Set card preview text size to **Extra Large**.
4. Group cards by the **Section** field so participant responses automatically sort into their respective breakout categories during the live synthesis block.