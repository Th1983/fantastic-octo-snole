{% ifversion fpt or ghec %}GitHub Actionsと合わせてアプリケーションを使っており、ワークフローファイルを変更したいのであれば、`workflow`スコープを含むOAuthトークンでユーザの代わりに認証を受けなければなりません。 ユーザは、ワークフローファイルを含むリポジトリの管理もしくは書き込み権限を持っていなければなりません。 詳しい情報については「[OAuthアプリケーションのスコープを理解する](/apps/building-oauth-apps/understanding-scopes-for-oauth-apps/#available-scopes)」を参照してください。{% endif %}