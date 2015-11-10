type = struct PROJECTILE_ESSENCE {
    unsigned int id;
    unsigned int type;
    namechar name[32];
    char file_model[128];
    char file_matter[128];
    char file_icon[128];
    char file_firegfx[128];
    char file_hitgfx[128];
    char file_hitsfx[128];
    int require_weapon_level_min;
    int require_weapon_level_max;
    int damage_enhance;
    int damage_scale_enhance;
    int price;
    int shop_price;
    unsigned int id_addon0;
    unsigned int id_addon1;
    unsigned int id_addon2;
    unsigned int id_addon3;
    int pile_num_max;
    unsigned int has_guid;
    unsigned int proc_type;
}
