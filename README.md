# Testing Plan

## Overview

This project follows a testing structure using the Jest testing framework and the @testing-library/react library.

## Structure

- `__tests__`: This directory contains all the test files.

## Test Types

1. **Unit Tests**: Tests individual functions or methods.
2. **Integration Tests**: Tests interactions between components.
3. **End-to-End (E2E) Tests**: Tests the entire application flow.

## Test Cases

### `TodoApp` Component

1. **Unit Test: Add Todo**
   - Test if a new todo is added successfully.

2. **Unit Test: Toggle Todo**
   - Test if toggling a todo changes its completed state.

3. **Integration Test: Filter Todos**
   - Test if filtering todos by status (All, Active, Completed) works correctly.
