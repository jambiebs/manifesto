addEventListener("fetch", event => {
  const data = {
       "name": "Cryptoglim",
         "short_name": "Cryptoglim",
           "description": "All About Crypto",
             "lang": "en-US",
               "display": "standalone",
                 "background_color": "#e30347",
                   "start_url": "/?utm_source=homescreen",
                     "theme_color": "#004aad",
                       "orientation": "portrait",
                         "icons": [
                             {
      "src": "https://raw.githubusercontent.com/jambiebs/cg-manifesto/main/favicon-32x32.png",
      "sizes": "32x32"
    },
    {
      "src": "https://raw.githubusercontent.com/jambiebs/cg-manifesto/main/android-chrome-192x192.png",
      "sizes": "192x192"
    },    
    {
      "src": "https://raw.githubusercontent.com/jambiebs/cg-manifesto/main/android-chrome-512x512.png",
      "sizes": "512x512"
                                                                                                                                                            },
                                                                                                                                                               ]
                                                                                                                                                                                                                                                                                                      }
  const json = JSON.stringify(data, null, 2)
  return event.respondWith(
      new Response(json, {
            headers: {
                    "content-type": "application/json;charset=UTF-8"
                          }
                              })
                                )
                                })
