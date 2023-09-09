JavaScriptSerializer js = new JavaScriptSerializer();
dynamic json_data = js.Deserialize(client.DownloadString(queryUri), typeof(object));

