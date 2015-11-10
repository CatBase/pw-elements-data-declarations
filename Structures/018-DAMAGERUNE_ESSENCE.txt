type = struct DAMAGERUNE_ESSENCE {
    unsigned int id;
    unsigned int id_sub_type;
    namechar name[32];
    char file_matter[128];
    char file_icon[128];
    unsigned int damage_type;
    int price;
    int shop_price;
    int require_weapon_level_min;
    int require_weapon_level_max;
    int damage_increased;
    int pile_num_max;
    unsigned int has_guid;
    unsigned int proc_type;
}
