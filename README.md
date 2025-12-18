# WebConfetti
----
A Xojo Library to fire confetti in your Xojo Web Apps. It's based on the [Confetti.js](https://confetti.js.org) MIT library, all kudos to them.

https://github.com/user-attachments/assets/b6cd1cd2-1022-4598-9498-2eb733a23e32

## How to use
----
Drop a WebConfetti instance in one of your web view, then call its Fire method.

## Properties

| Name | Type | Read-Only | Shared |
|------|------|-----------|--------|
| ParticleCount | Integer | No | No |
| Spread | Integer | No | No |

### ParticleCount
The amount of particles that will be fired the next time you call the Fire method.

### Spread
This will make the fire cone to be wider. The higher value, the wider the confetti cone will be.

## Methods

| Name | Parameters | Returns | Shared Method |
|------|------------|---------|---------------|
| Fire | x As Integer, y As Integer | - | No |

### Fire

Fires confetti at the position specified.
```xojo
// Fires confetti at the middle of the browser
Confetti.Fire(Session.ClientWidth / 2, Session.ClientHeight / 2)
```
