add_library(webview_test_driver STATIC)
target_sources(webview_test_driver PRIVATE src/test_driver.cc)
target_include_directories(webview_test_driver PUBLIC include)
