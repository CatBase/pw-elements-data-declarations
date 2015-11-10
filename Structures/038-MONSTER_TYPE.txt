type = struct MONSTER_TYPE {
    unsigned int id;
    namechar name[32];
    struct {
        unsigned int id_addon;
        float probability_addon;
    } addons[16];
}
