type = struct STONE_ESSENCE {
    unsigned int id;
    unsigned int id_sub_type;
    namechar name[32];
    char file_matter[128];
    char file_icon[128];
    int level;
    int color;
    int price;
    int shop_price;
    int install_price;
    int uninstall_price;
    unsigned int id_addon_damage;
    unsigned int id_addon_defence;
    namechar weapon_desc[16];
    namechar armor_desc[16];
    int pile_num_max;
    unsigned int has_guid;
    unsigned int proc_type;
}
