type = struct FACETICKET_ESSENCE {
    unsigned int id;
    unsigned int id_major_type;
    unsigned int id_sub_type;
    namechar name[32];
    char file_matter[128];
    char file_icon[128];
    int require_level;
    char bound_file[128];
    unsigned int unsymmetrical;
    int price;
    int shop_price;
    int pile_num_max;
    unsigned int has_guid;
    unsigned int proc_type;
}
