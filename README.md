# GitTutorial
Git Work Flow
<img src=/gitworkflow.png><img>

<table>
    <thead>
        <tr>
            <th>Commands</th>
            <th>Description and Exmaples</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>
                <strong>git add</strong>
            </td>
            <td>Stage changes for next commit<br>
                <em>
                    <kbd>git add .<br>git add file_name<br>git add c:\local_repo_name\repo_folder_name/sub_folder_name</kbd>
                </em>
            </td>
        </tr>
            <tr><td><strong>git commit</strong></td><td>Commit the staged snapshot to the local repository<br><em><kbd>git commit -m "commit message"</kbd></em></td></tr><tr><td><strong>git push</strong></td><td>Upload local repository content to a remote repository<br><em><kbd>git push origin master<br>git push -u origin local_branch_name</kbd></em></td></tr><tr><td><strong>git fetch</strong></td><td>Download content from remote repository, but doesn’t force the merge<br><em><kbd>git fetch origin master</kbd></em></td></tr><tr><td><strong>git merge</strong></td><td>Join two branches together<br><em><kbd>git merge local_branch_name</kbd></em><br><em><kbd>git merge local_branch_1 local_branch_2</kbd></em></td></tr><tr><td><strong>git pull</strong></td><td>Combo of git fetch and git merge<br><em><kbd>git pull <br>git pull origin remote_branch_name</kbd></em></td></tr></tbody></table>