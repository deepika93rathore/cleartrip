# cleartrip

Conference room management system

Each conference room is unique id — roomId, floorId & buildingId -- [Done]
Book slots in hours —> 24 hour format —> {12:13} --> [Done]
Conference room can be booked only by one userId at all times --> [Done]
Max booking 12 hours --> [Not Done]
getConfernceRooms(userid, buildingId) —> List of conference rooms -->[Done]
getConfernceRooms(userid, buildingId, slot) —> available rooms in the slot --> [Done]
cancelRoom(userid, bookingId) --> [Done]
listAllRoomsBoooked(userId) --> [Done]
