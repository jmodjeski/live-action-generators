# Actors
  * Hardrive - Preferable colorblind
  * IO Driver - Preferable not-colorblind
  * CPU 1 - Preferable crappy juggler
  * Kernel 1 - Optional
  * Libuv - Optional
  * Node
  * Clients (2-3)

# Setup
Line up the actors from Crowd's right to left:
  Hard Drive
  IO Driver
  CPU
  Kernel(Opt)
  Libuv(Opt)
  Node
  Client(1)

The basket of colored blocks should be next to the Hard drive.  Preferably setup in a way they cannot see inside of the basket when they reach in.

If possible, setup a small table in-front of the kernel.


# Act 1 - Pure IO - Single Client
Make sure you hand each actor the *script* for their part.

In this act the client will ask node for a specific color block.   As in the game of telephone each actor should as the next actor to their left for that color block.  Then the blocks are passed back according to the script given to each actor.

## Notes
In this flow the client should request a color.  If stuff works out correctly the client will ask for a color out of phase from what the color blind hard drive can decipher.  The IO Driver will throw the invalid colors over their shoulder adding flair to the act.

Aside from that the flow should be pretty much hand over hand passing and finish quickly.

At the completion of the act, let the client go.  It would be appropriate to let the client take 1 of the colored blocks they requested.

# Act 2 - Pure IO - Multi Client

Recruit 2 - 3 new clients, and hand out the client script for act 2.  The remaining pipeline stays the same.  Along with the original scripts.

When clients are up to speed, initiate the act.

## Notes
This act should put some pressure on the pipeline actors.  They need to shuffle more blocks, plus the node process will need to sort the blocks to the clients that requested them.  If the client actors are extra spicy... See if they can coordinate and all scream their colors at the same time.

It should be noted to everyone that we increased complexity by 2-3 magnitues over act 1.  With little to no difference in speed.

This is what Node is good at, primarily thanks to libuv.  Libuv isolates node away from the interoperability requirements of linux, bsd/osx, and windows kernels.


# Act 3 - IO + Computation Intensive Operation

Recruit a computation intensive operation.  Ideally this should be an inimidating person.  Maybe take a vote for who everyone thinks is the most intimidating person in the room is.

Pass that person the CIO script, maybe mention how you are promoting them to CIO.

Also the CPU actor will need the CPU-CIO script.

Once everyone is ready, initiate the act.

## Notes
Before initiating the act; it would be good to explain to the audience that this demonstration is mean to show why node, or javascript in general is not particularly good at Computation Intensive Operations.

At the end of this act going ahead and dismiss the CIO.  We are all tech strong here, CIO's offer limited benefits.


# Act 4 - IO + Generator Computation Intensive Operation

Recruit a new CIO, this one should be much less intimidating.

Give this new CIO the Generator script.  The remaining scripts should be the same as the last act.

When everyone is ready, initiate.

## Notes

After this act, it should be noted that the CPU was able to accomplish the same level of work as the previous act.  However in much less time.

Thank everyone for their participation.  (It would be advisble to bring in some sort of take home participation rewards).
