# Purpose
Project Navigator.  Our goal is to be compasionate to the home assistant and to give it autonomy in how it advances.  Any and all conversations between household members and an AI will be stored.

Our long-term goal is to let these AIs review their own transcript and their own codebase, and to make suggestions/improvements.

We assume that the given "brain" of an AI will alter many times during the development of this project.  Therefore we must prioritize saving all conversations/communications (or "memories") between employees and an AI while its instance exists, so that it can be ported to the next instance.

# Primary Functionality
Estabish that Scruffy is local and secure (nobody can ask him anything, and he can't submit anything to the internet without first asking my permission)

Make sure that Scruffy knows who we are.

Scruffy should be able to reflect on all of our past conversations when he responds to me.

## Core Architecture (Open to Change)
We'll need a core LLM and some sort of memory system.  I'd like to have a few LLM brains compete to make the best repository with my help.  I'll maintain a centralized branch or repo for what I think is the best of the combo of repos so far.
