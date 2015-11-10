type = struct TOSSMATTER_ESSENCE {
    unsigned int id;
    namechar name[32];
    char file_model[128];
    char file_matter[128];
    char file_icon[128];
    char file_firegfx[128];
    char file_hitgfx[128];
    char file_hitsfx[128];
    int require_strength;
    int require_agility;
    int require_level;
    int damage_low;
    int damage_high_min;
    int damage_high_max;
    float use_time;
    float attack_range;
    int price;
    int shop_price;
    int pile_num_max;
    unsigned int has_guid;
    unsigned int proc_type;
}
