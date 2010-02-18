include_directories(${CMAKE_CURRENT_SOURCE_DIR}/../mbfl)
SET(mbfl_nls_files nls_ja.c nls_de.c nls_en.c nls_hy.c nls_tr.c nls_kr.c nls_ru.c nls_ua.c nls_zh.c nls_uni.c nls_neutral.c)
	
add_library(mbfl_nls STATIC ${mbfl_nls_files})