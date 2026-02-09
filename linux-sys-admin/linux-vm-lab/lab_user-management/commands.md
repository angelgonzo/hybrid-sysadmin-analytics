## Commands

## Creating a new user

useradd -c "Nimbus Stratus" -m nstratus

useradd -c "Roger Ruby" -m rruby

## Creating groups
groupadd -g 1010 QA

groupadd -g 1011 Developer

## Modifying user's groups
usermod -g 1010 nstratus

usermod -g 1011 rruby

## Viewing user groups
groups nstratus

groups rruby

