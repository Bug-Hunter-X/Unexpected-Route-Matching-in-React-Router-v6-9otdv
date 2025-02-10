# Unexpected Route Matching in React Router v6

This repository demonstrates a common issue encountered when working with nested routes or route parameters in React Router v6.  The problem involves incorrect route matching, leading to unexpected component rendering.  The solution shows how to correctly structure routes and use path parameters to prevent these issues.

## Problem

The bug is related to how React Router v6 handles route matching, particularly when using nested routes or route parameters.  In some cases, it may incorrectly match routes, leading to the wrong component being rendered.

## Solution

The solution focuses on using precise path matching and appropriate route ordering.  The `useParams` hook is used correctly to access dynamic segments from the URL.

## Setup

1. Clone this repository.
2. Run `npm install` to install dependencies.
3. Run `npm start` to start the development server.