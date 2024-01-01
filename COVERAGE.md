# Coverage

| C Function Name            | Fortran Interface Name                   | Bound |
|----------------------------|------------------------------------------|-------|
| `curl_easy_cleanup`        | `curl_easy_cleanup`                      | ✓     |
| `curl_easy_duphandle`      |                                          |       |
| `curl_easy_escape`         | `curl_easy_escape`                       | ✓     |
| `curl_easy_getinfo`        | `curl_easy_getinfo`                      | ✓     |
| `curl_easy_init`           | `curl_easy_init`                         | ✓     |
| `curl_easy_pause`          | `curl_easy_pause`                        | ✓     |
| `curl_easy_perform`        | `curl_easy_perform`                      | ✓     |
| `curl_easy_recv`           |                                          |       |
| `curl_easy_reset`          |                                          |       |
| `curl_easy_send`           |                                          |       |
| `curl_easy_setopt`         | `curl_easy_setopt`, `curl_easy_setopt_*` | ✓     |
| `curl_easy_strerror`       | `curl_easy_strerror`                     | ✓     |
| `curl_easy_unescape`       | `curl_easy_unescape`                     | ✓     |
| `curl_easy_upkeep`         |                                          |       |
| `curl_escape`              | `curl_escape`                            | ✓     |
| `curl_formadd`             |                                          |       |
| `curl_free`                | `curl_free`                              | ✓     |
| `curl_getdate`             |                                          |       |
| `curl_getenv`              |                                          |       |
| `curl_global_cleanup`      | `curl_global_cleanup`                    | ✓     |
| `curl_global_init`         | `curl_global_init`                       | ✓     |
| `curl_global_init_mem`     |                                          |       |
| `curl_global_sslset`       |                                          |       |
| `curl_global_trace`        |                                          |       |
| `curl_mime_addpart`        | `curl_mime_addpart`                      | ✓     |
| `curl_mime_data`           | `curl_mime_data`                         | ✓     |
| `curl_mime_data_cb`        |                                          |       |
| `curl_mime_encoder`        | `curl_mime_encoder`                      | ✓     |
| `curl_mime_filedata`       | `curl_mime_filedata`                     | ✓     |
| `curl_mime_filename`       | `curl_mime_filename`                     | ✓     |
| `curl_mime_free`           | `curl_mime_free`                         | ✓     |
| `curl_mime_headers`        | `curl_mime_headers`                      | ✓     |
| `curl_mime_init`           | `curl_mime_init`                         | ✓     |
| `curl_mime_name`           | `curl_mime_name`                         | ✓     |
| `curl_mime_subparts`       | `curl_mime_subparts`                     | ✓     |
| `curl_mime_type`           | `curl_mime_type`                         | ✓     |
| `curl_multi_add_handle`    | `curl_multi_add_handle`                  | ✓     |
| `curl_multi_assign`        |                                          |       |
| `curl_multi_cleanup`       | `curl_multi_cleanup`                     | ✓     |
| `curl_multi_fdset`         |                                          |       |
| `curl_multi_info_read`     | `curl_multi_info_read`                   | ✓     |
| `curl_multi_init`          | `curl_multi_init`                        | ✓     |
| `curl_multi_perform`       | `curl_multi_perform`                     | ✓     |
| `curl_multi_poll`          | `curl_multi_pause`                       | ✓     |
| `curl_multi_remove_handle` | `curl_multi_remove_handle`               | ✓     |
| `curl_multi_socket_action` |                                          |       |
| `curl_multi_setopt`        |                                          |       |
| `curl_multi_strerror`      | `curl_multi_strerror`                    | ✓     |
| `curl_multi_timeout`       | `curl_multi_timeout`                     | ✓     |
| `curl_multi_wakeup`        | `curl_multi_wakeup`                      | ✓     |
| `curl_multi_wait`          |                                          |       |
| `curl_pushheader_byname`   |                                          |       |
| `curl_pushheader_bynum`    |                                          |       |
| `curl_share_cleanup`       |                                          |       |
| `curl_share_init`          |                                          |       |
| `curl_share_setopt`        |                                          |       |
| `curl_share_strerror`      |                                          |       |
| `curl_slist_append`        | `curl_slist_append`                      | ✓     |
| `curl_slist_free_all`      | `curl_slist_free_all`                    | ✓     |
| `curl_strequal`            |                                          |       |
| `curl_strnequal`           |                                          |       |
| `curl_unescape`            | `curl_unescape`                          | ✓     |
| `curl_url`                 | `curl_url`                               | ✓     |
| `curl_url_cleanup`         | `curl_url_cleanup`                       | ✓     |
| `curl_url_dup`             | `curl_url_dup`                           | ✓     |
| `curl_url_get`             | `curl_url_get`                           | ✓     |
| `curl_url_set`             | `curl_url_get`                           | ✓     |
| `curl_url_strerror`        | `curl_url_strerror`                      | ✓     |
| `curl_version`             | `curl_version`                           | ✓     |
| `curl_version_info`        | `curl_version_info`                      | ✓     |

| C Constant Name            | Fortran Interface Name                   | Bound |
|----------------------------|------------------------------------------|-------|
| `CURLVERSION_NOW`          | `curl_version_now`                       | ✓     |
| `LIBCURL_TIMESTAMP`        |                                          |       |
| `LIBCURL_VERSION`          |                                          |       |
| `LIBCURL_VERSION_MAJOR`    |                                          |       |
| `LIBCURL_VERSION_MINOR`    |                                          |       |
| `LIBCURL_VERSION_NUM`      |                                          |       |
| `LIBCURL_VERSION_PATCH`    |                                          |       |