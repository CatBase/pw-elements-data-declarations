type = struct MEDICINE_ESSENCE {
    unsigned int id;
    unsigned int id_major_type;
    unsigned int id_sub_type;
    namechar name[32];
    char file_matter[128];
    char file_icon[128];
    int require_level;
    int cool_time;
    int hp_add_total;
    int hp_add_time;
    int mp_add_total;
    int mp_add_time;
    int price;
    int shop_price;
    int pile_num_max;
    unsigned int has_guid;
    unsigned int proc_type;
}
