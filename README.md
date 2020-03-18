# remoteupdateapk
lib para atualização remota de app Android

# uso

Intent intent = new Intent(this, RemoteUpdateActivity.class);
intent.putExtra("URL", URL_DO_APK);
startActivity(intent);

