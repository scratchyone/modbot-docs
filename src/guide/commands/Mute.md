# Mute Commands

## Setup Mute Role

You can setup the mute role by running `m: setupmute` when there is no mute role configured and clicking on the :hammer: react.

## Remove Mute Role

You can delete the mute role by running `m: setupmute` when there is a mute role configured and clicking on the :wastebasket: react.

## Fix Mute Role Permissions

You can fix the permissions of the currently configured mute role by running `m: setupmute` when there is a mute role configured and clicking on the :hammer: react.

## Mute User

You can mute a user by running `m: mute <USER> [DURATION]`. The duration cannot have any spaces in it.

### Examples

#### Mute BadPerson for 12 hours

```
m: mute @BadPerson 12h
```

#### Mute BadPerson indefinitely

```
m: mute @BadPerson
```

## Unmute User

You can unmute a user by running `m: unmute <USER>`.

### Examples

#### Unmute GoodPerson

```
m: unmute @GoodPerson
```
