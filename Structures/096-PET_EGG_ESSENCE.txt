type = struct PET_EGG_ESSENCE {
    unsigned int id;
    namechar name[32];
    char file_matter[128];
    char file_icon[128];
    int id_pet;
    int money_hatched;
    int money_restored;
    int honor_point;
    int level;
    int exp;
    int skill_point;
    struct {
        int id_skill;
        int level;
    } skills[32];
    int price;
    int shop_price;
    int pile_num_max;
    unsigned int has_guid;
    unsigned int proc_type;
}
