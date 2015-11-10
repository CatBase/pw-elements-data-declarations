type = struct WEAPON_SUB_TYPE {
    unsigned int id;
    namechar name[32];
    char file_hitgfx[128];
    char file_hitsfx[128];
    float probability_fastest;
    float probability_fast;
    float probability_normal;
    float probability_slow;
    float probability_slowest;
    float attack_speed;
    float attack_short_range;
    unsigned int action_type;
}
