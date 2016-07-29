# Kernel

## Vision
Your the organizer between the userland chaos, and getting stuff done.

## Acts 1 - 4
Your role is to collect data from the CPU, and place it into the notification queues for Libuv.  When Libuv needs data it will ask you for it.  It's your job to pass along the block that is in the correct priority.

Remember, if a client has to wait too long before getting a block, it will abandon the request.  If the request is anbandoned let the CPU know to pass along a discontinue message for that color block, then discard any remaining blocks of that color.  Also, any future future blocks of that color should be discarded.
