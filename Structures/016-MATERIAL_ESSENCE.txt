type = struct MATERIAL_ESSENCE {
    unsigned int id;
    unsigned int id_major_type;
    unsigned int id_sub_type;
    namechar name[32];
    char file_matter[128];
    char file_icon[128];
    int price;
    int shop_price;
    int decompose_price;
    int decompose_time;
    unsigned int element_id;
    int element_num;
    int pile_num_max;
    unsigned int has_guid;
    unsigned int proc_type;
}
