type = struct NPC_RESETPROP_SERVICE {
    unsigned int id;
    namechar name[32];
    struct {
        int id_object_need;
        int strength_delta;
        int agility_delta;
        int vital_delta;
        int energy_delta;
    } prop_entry[15];
}
