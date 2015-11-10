type = struct ARMORRUNE_ESSENCE {
    unsigned int id;
    unsigned int id_sub_type;
    namechar name[32];
    char file_matter[128];
    char file_icon[128];
    char file_gfx[128];
    char file_sfx[128];
    unsigned int damage_type;
    int price;
    int shop_price;
    int require_player_level_min;
    int require_player_level_max;
    float damage_reduce_percent;
    int damage_reduce_time;
    int pile_num_max;
    unsigned int has_guid;
    unsigned int proc_type;
}
