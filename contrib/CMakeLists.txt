
PROJECT(modules/contrib)

CMAKE_MINIMUM_REQUIRED(VERSION 2.6)
INCLUDE(ModMacros)

INCLUDE_DIRECTORIES(${libratbox_SOURCE_DIR}/include)
INCLUDE_DIRECTORIES(${libratbox_BINARY_DIR} ${bluebox_BINARY_DIR})
INCLUDE_DIRECTORIES(${bluebox_SOURCE_DIR}/include)

CREATE_MODULE(example_module example_module.c modules/contrib)
CREATE_MODULE(m_42 m_42.c modules/contrib)
CREATE_MODULE(m_clearchan m_clearchan.c modules/contrib)
CREATE_MODULE(m_flags m_flags.c modules/contrib)
CREATE_MODULE(m_force m_force.c modules/contrib)
CREATE_MODULE(m_hdump m_hdump.c modules/contrib)
CREATE_MODULE(m_mkpasswd m_mkpasswd.c modules/contrib)
CREATE_MODULE(m_ojoin m_ojoin.c modules/contrib)
CREATE_MODULE(m_okick m_okick.c modules/contrib)
CREATE_MODULE(m_olist m_olist.c modules/contrib)
CREATE_MODULE(m_opme m_opme.c modules/contrib)
CREATE_MODULE(m_rsshortcut m_rsshortcut.c modules/contrib)
CREATE_MODULE(m_webirc m_webirc.c modules/contrib)
CREATE_MODULE(spy_admin_notice spy_admin_notice.c modules/contrib)
CREATE_MODULE(spy_info_notice spy_info_notice.c modules/contrib)
CREATE_MODULE(spy_links_notice spy_links_notice.c modules/contrib)
CREATE_MODULE(spy_motd_notice spy_motd_notice.c modules/contrib)
CREATE_MODULE(spy_stats_notice spy_stats_notice.c modules/contrib)
CREATE_MODULE(spy_stats_p_notice spy_stats_p_notice.c modules/contrib)
CREATE_MODULE(spy_whois_notice spy_whois_notice.c modules/contrib)
CREATE_MODULE(spy_whois_notice_global spy_whois_notice_global.c modules/contrib)
