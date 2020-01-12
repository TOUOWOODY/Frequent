private Vector3 target;

    public void Frequent()
    {
        transform.localPosition = Vector3.MoveTowards(transform.localPosition, target, 10f);

        // 10의 속도로 타켓 방향 이동
    }
