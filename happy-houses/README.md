# Happy-Houses

This is an architectural coding challenge.

The goal is to implement a system for furnishing houses with variable numbers and types of rooms.

The room types are statically defined in the room_types.h header file.

An input file containing a house definition is given on the command line to the main function.

Your task is to determine how best to furnish the house, given a furnishing budget.

Different furnishings have different scores, but those scores are weighted. For instance, if a bedroom does not have a 
bed, adding one might give 10 points. However, adding a second bed to that room may provide only two points.
