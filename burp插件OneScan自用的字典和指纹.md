字典
```
/api-docs
/api/v1/api-docs
/api/v2/api-docs
/api/v3/api-docs
/file/upload
/swagger-resources
/swagger-ui.html
/swagger-ui/index.html
/swagger.json
/upload
/v1/api-docs
/v2/api-docs
/v3/api-docs
/nacos
/druid
/xxl-job-admin
/axis
/api/axis
/swagger/ui/index
/webjars/swagger-ui/index.html
/geoserver/web/
/version
/_nodes
/manage
/jmx_console
/_config
/app/home%23/
/sys
/c/manage/
/config.json
/actuator
/Admin
/ant4/
/h5
/map
/api/doc.html

```

检测指纹
```
Api-doc: body.contains("swaggerVersion")
api-docs?group=: body.contains("api-docs?group=")
xxl-job-admin: header.contains("Location: /xxl-job-admin/toLogin")
```
