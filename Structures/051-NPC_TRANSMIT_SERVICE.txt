type = struct NPC_TRANSMIT_SERVICE {
    unsigned int id;
    namechar name[32];
    int num_targets;
    struct {
        int idTarget;
        int fee;
        int required_level;
    } targets[32];
    unsigned int id_dialog;
}
