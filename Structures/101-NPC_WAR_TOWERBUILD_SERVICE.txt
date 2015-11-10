type = struct NPC_WAR_TOWERBUILD_SERVICE {
    unsigned int id;
    namechar name[32];
    struct {
        int id_in_build;
        int id_buildup;
        int id_object_need;
        int time_use;
        int fee;
    } build_info[4];
}
