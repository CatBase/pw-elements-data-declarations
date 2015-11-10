type = struct SUITE_ESSENCE {
    unsigned int id;
    namechar name[32];
    int max_equips;
    struct {
        unsigned int id;
    } equipments[12];
    struct {
        unsigned int id;
    } addons[11];
    char file_gfx[128];
}
