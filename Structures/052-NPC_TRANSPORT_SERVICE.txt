type = struct NPC_TRANSPORT_SERVICE {
    unsigned int id;
    namechar name[32];
    struct {
        unsigned int id;
        unsigned int fee;
    } routes[32];
    unsigned int id_dialog;
}
